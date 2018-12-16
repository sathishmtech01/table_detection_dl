# Table detection using deep learning

    https://blog.goodaudience.com/table-detection-using-deep-learning-7182918d778

### Create & activate conda environment
    csk@csk-ai-revolution:~/PycharmProjects/table_detection_dl$ source activate table_detection_dl

### Installation

    (table_detection_dl) csk@csk-ai-revolution:~/PycharmProjects/table_detection_dl$ pip install -r requirements.txt
    
### Preparing training data
    (table_detection_dl) csk@csk-ai-revolution:~/PycharmProjects/table_detection_dl$ lumi dataset transform --type csv --data-dir data/ --output-dir tfdata/ --split train --split val --only-classes=table
    data/train.csv
    <tensorflow.python.platform.gfile.GFile object at 0x7f86a0a709e8>
    <csv.DictReader object at 0x7f86a0a70470>
    OrderedDict([('image_id', '0101_003.png'), ('xmin', '770'), ('ymin', '946'), ('xmax', '2070'), ('ymax', '2973'), ('label', 'table')])
    INFO:tensorflow:Saving split "train" in output_dir = tfdata/
      [####################################]  100%             
    INFO:tensorflow:Saved 338 records to "tfdata/train.tfrecords"
    INFO:tensorflow:Composition per class (train):
    INFO:tensorflow:        table: 418
    INFO:tensorflow:Saving split "val" in output_dir = tfdata/
    data/val.csv
    <tensorflow.python.platform.gfile.GFile object at 0x7f86a0a70a20>
    <csv.DictReader object at 0x7f86a0a70470>

### Training the network
    
    (table_detection_dl) csk@csk-ai-revolution:~/PycharmProjects/table_detection_dl$ lumi train -c config.yml
    WARNING:tensorflow:From /home/csk/anaconda/envs/table_detection_dl/lib/python3.6/site-packages/luminoth/datasets/base_dataset.py:44: string_input_producer (from tensorflow.python.training.input) is deprecated and will be removed in a future version.
    Instructions for updating:
    Queue-based input pipelines have been replaced by `tf.data`. Use `tf.data.Dataset.from_tensor_slices(string_tensor).shuffle(tf.shape(input_tensor, out_type=tf.int64)[0]).repeat(num_epochs)`. If `shuffle=False`, omit the `.shuffle(...)`.


### Using the trained network to make predictions
    (table_detection_dl) csk@csk-ai-revolution:~/PycharmProjects/table_detection_dl$ lumi checkpoint create config.yml
    Creating checkpoint for given configuration...
    Checkpoint d710e6949665 created successfully.
    

### Use the check point and predict
    (table_detection_dl) csk@csk-ai-revolution:~/PycharmProjects/table_detection_dl$ lumi predict --checkpoint d710e6949665 data/train/1012_041.png 
    Found 1 files to predict.
    2018-12-16 18:50:40.945438: I tensorflow/core/platform/cpu_feature_guard.cc:141] Your CPU supports instructions that this TensorFlow binary was not compiled to use: AVX2 FMA
    Predicting data/train/1012_041.png...2018-12-16 18:50:50.497352: W tensorflow/core/framework/allocator.cc:122] Allocation of 390168576 exceeds 10% of system memory.
     done.
    {"file": "data/train/1012_041.png", "objects": []}
