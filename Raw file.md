    csk@csk-ai-revolution:~$ sudo apt-get update
    [sudo] password for csk: 
    Sorry, try again.
    [sudo] password for csk: 
    Ign:1 http://dl.google.com/linux/chrome/deb stable InRelease
    Get:2 http://ppa.launchpad.net/mozillateam/firefox-next/ubuntu xenial InRelease [23.8 kB]
    Hit:3 http://archive.ubuntu.com/ubuntu xenial InRelease                        
    Get:4 http://dl.google.com/linux/chrome/deb stable Release [943 B]             
    Get:5 http://security.ubuntu.com/ubuntu xenial-security InRelease [107 kB]     
    Get:6 http://dl.google.com/linux/chrome/deb stable Release.gpg [819 B]         
    Get:7 http://archive.ubuntu.com/ubuntu xenial-updates InRelease [109 kB]       
    Get:8 http://dl.google.com/linux/chrome/deb stable/main amd64 Packages [1,113 B]
    Get:9 https://repo.skype.com/deb stable InRelease [4,487 B]                    
    Get:10 https://repo.skype.com/deb stable/main amd64 Packages [2,259 B]         
    Get:11 http://archive.canonical.com/ubuntu xenial InRelease [11.5 kB]          
    Get:12 http://ppa.launchpad.net/mozillateam/firefox-next/ubuntu xenial/main amd64 Packages [13.3 kB]
    Ign:13 http://dell.archive.canonical.com/updates xenial-dell InRelease         
    Get:14 http://archive.ubuntu.com/ubuntu xenial-backports InRelease [107 kB]    
    Get:15 http://security.ubuntu.com/ubuntu xenial-security/main amd64 Packages [589 kB]
    Hit:16 http://dell.archive.canonical.com/updates xenial-dell Release           
    Get:18 http://ppa.launchpad.net/mozillateam/firefox-next/ubuntu xenial/main i386 Packages [13.3 kB]
    Get:19 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 Packages [892 kB]
    Get:20 http://archive.canonical.com/ubuntu xenial/partner amd64 Packages [3,136 B]
    Get:21 http://archive.canonical.com/ubuntu xenial/partner i386 Packages [3,120 B]
    Get:22 http://security.ubuntu.com/ubuntu xenial-security/main i386 Packages [502 kB]
    Get:23 http://archive.ubuntu.com/ubuntu xenial-updates/main i386 Packages [790 kB]
    Get:24 http://security.ubuntu.com/ubuntu xenial-security/main Translation-en [245 kB]
    Get:25 http://security.ubuntu.com/ubuntu xenial-security/main amd64 DEP-11 Metadata [67.7 kB]
    Get:26 http://archive.ubuntu.com/ubuntu xenial-updates/main Translation-en [361 kB]
    Get:27 http://security.ubuntu.com/ubuntu xenial-security/main DEP-11 64x64 Icons [68.0 kB]
    Get:28 http://security.ubuntu.com/ubuntu xenial-security/universe amd64 Packages [408 kB]
    Get:29 http://security.ubuntu.com/ubuntu xenial-security/universe i386 Packages [354 kB]
    Get:30 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 DEP-11 Metadata [320 kB]
    Get:31 http://security.ubuntu.com/ubuntu xenial-security/universe Translation-en [159 kB]
    Get:32 http://archive.ubuntu.com/ubuntu xenial-updates/main DEP-11 64x64 Icons [234 kB]
    Get:33 http://archive.ubuntu.com/ubuntu xenial-updates/universe amd64 Packages [715 kB]
    Get:34 http://security.ubuntu.com/ubuntu xenial-security/universe amd64 DEP-11 Metadata [109 kB]
    Get:35 http://security.ubuntu.com/ubuntu xenial-security/universe DEP-11 64x64 Icons [154 kB]
    Get:36 http://security.ubuntu.com/ubuntu xenial-security/multiverse amd64 Packages [3,724 B]
    Get:37 http://security.ubuntu.com/ubuntu xenial-security/multiverse i386 Packages [3,888 B]
    Get:38 http://security.ubuntu.com/ubuntu xenial-security/multiverse Translation-en [1,844 B]
    Get:33 http://archive.ubuntu.com/ubuntu xenial-updates/universe amd64 Packages [715 kB]
    Get:39 http://archive.ubuntu.com/ubuntu xenial-updates/universe i386 Packages [655 kB]
    Get:40 http://archive.ubuntu.com/ubuntu xenial-updates/universe Translation-en [292 kB]
    Get:41 http://archive.ubuntu.com/ubuntu xenial-updates/universe amd64 DEP-11 Metadata [248 kB]
    Get:42 http://archive.ubuntu.com/ubuntu xenial-updates/universe DEP-11 64x64 Icons [336 kB]
    Get:43 http://archive.ubuntu.com/ubuntu xenial-updates/multiverse amd64 Packages [16.6 kB]
    Get:44 http://archive.ubuntu.com/ubuntu xenial-updates/multiverse i386 Packages [15.7 kB]
    Get:45 http://archive.ubuntu.com/ubuntu xenial-updates/multiverse Translation-en [8,440 B]
    Get:46 http://archive.ubuntu.com/ubuntu xenial-updates/multiverse amd64 DEP-11 Metadata [5,968 B]
    Get:47 http://archive.ubuntu.com/ubuntu xenial-updates/multiverse DEP-11 64x64 Icons [14.3 kB]
    Get:48 http://archive.ubuntu.com/ubuntu xenial-backports/main amd64 Packages [7,288 B]
    Get:49 http://archive.ubuntu.com/ubuntu xenial-backports/main i386 Packages [7,292 B]
    Get:50 http://archive.ubuntu.com/ubuntu xenial-backports/main Translation-en [4,456 B]
    Get:51 http://archive.ubuntu.com/ubuntu xenial-backports/main amd64 DEP-11 Metadata [3,324 B]
    Get:52 http://archive.ubuntu.com/ubuntu xenial-backports/universe amd64 Packages [7,804 B]
    Get:53 http://archive.ubuntu.com/ubuntu xenial-backports/universe i386 Packages [7,488 B]
    Get:54 http://archive.ubuntu.com/ubuntu xenial-backports/universe Translation-en [4,184 B]
    Get:55 http://archive.ubuntu.com/ubuntu xenial-backports/universe amd64 DEP-11 Metadata [5,104 B]
    Fetched 7,905 kB in 3min 5s (42.7 kB/s)                                        
    Reading package lists... Done
    csk@csk-ai-revolution:~$ python3 -m venv env
    Error: Command '['/home/csk/env/bin/python3', '-Im', 'ensurepip', '--upgrade', '--default-pip']' returned non-zero exit status 1.
    csk@csk-ai-revolution:~$ python3
    Python 3.6.5 |Anaconda, Inc.| (default, Apr 29 2018, 16:14:56) 
    [GCC 7.2.0] on linux
    Type "help", "copyright", "credits" or "license" for more information.
    >>> 
    [1]+  Stopped                 python3
    csk@csk-ai-revolution:~$ sudo apt-get install python3-venv
    Reading package lists... Done
    Building dependency tree       
    Reading state information... Done
    The following additional packages will be installed:
      libpython3.5 libpython3.5-minimal libpython3.5-stdlib python-pip-whl
      python3.5 python3.5-minimal python3.5-venv
    Suggested packages:
      python3.5-doc binfmt-support
    The following NEW packages will be installed:
      python-pip-whl python3-venv python3.5-venv
    The following packages will be upgraded:
      libpython3.5 libpython3.5-minimal libpython3.5-stdlib python3.5
      python3.5-minimal
    5 upgraded, 3 newly installed, 0 to remove and 563 not upgraded.
    Need to get 6,899 kB of archives.
    After this operation, 1,263 kB of additional disk space will be used.
    Do you want to continue? [Y/n] Y
    Get:1 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 libpython3.5 amd64 3.5.2-2ubuntu0~16.04.5 [1,360 kB]
    Get:2 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 python3.5 amd64 3.5.2-2ubuntu0~16.04.5 [165 kB]
    Get:3 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 libpython3.5-stdlib amd64 3.5.2-2ubuntu0~16.04.5 [2,134 kB]
    Get:4 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 python3.5-minimal amd64 3.5.2-2ubuntu0~16.04.5 [1,598 kB]
    Get:5 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 libpython3.5-minimal amd64 3.5.2-2ubuntu0~16.04.5 [524 kB]
    Get:6 http://archive.ubuntu.com/ubuntu xenial-updates/universe amd64 python-pip-whl all 8.1.1-2ubuntu0.4 [1,110 kB]
    Get:7 http://archive.ubuntu.com/ubuntu xenial-updates/universe amd64 python3.5-venv amd64 3.5.2-2ubuntu0~16.04.5 [5,994 B]
    Get:8 http://archive.ubuntu.com/ubuntu xenial/universe amd64 python3-venv amd64 3.5.1-3 [1,106 B]
    Fetched 6,899 kB in 1min 6s (104 kB/s)                                         
    (Reading database ... 215587 files and directories currently installed.)
    Preparing to unpack .../libpython3.5_3.5.2-2ubuntu0~16.04.5_amd64.deb ...
    Unpacking libpython3.5:amd64 (3.5.2-2ubuntu0~16.04.5) over (3.5.2-2ubuntu0~16.04.4) ...
    Preparing to unpack .../python3.5_3.5.2-2ubuntu0~16.04.5_amd64.deb ...
    Unpacking python3.5 (3.5.2-2ubuntu0~16.04.5) over (3.5.2-2ubuntu0~16.04.4) ...
    Preparing to unpack .../libpython3.5-stdlib_3.5.2-2ubuntu0~16.04.5_amd64.deb ...
    Unpacking libpython3.5-stdlib:amd64 (3.5.2-2ubuntu0~16.04.5) over (3.5.2-2ubuntu0~16.04.4) ...
    Preparing to unpack .../python3.5-minimal_3.5.2-2ubuntu0~16.04.5_amd64.deb ...
    Unpacking python3.5-minimal (3.5.2-2ubuntu0~16.04.5) over (3.5.2-2ubuntu0~16.04.4) ...
    Preparing to unpack .../libpython3.5-minimal_3.5.2-2ubuntu0~16.04.5_amd64.deb ...
    Unpacking libpython3.5-minimal:amd64 (3.5.2-2ubuntu0~16.04.5) over (3.5.2-2ubuntu0~16.04.4) ...
    Selecting previously unselected package python-pip-whl.
    Preparing to unpack .../python-pip-whl_8.1.1-2ubuntu0.4_all.deb ...
    Unpacking python-pip-whl (8.1.1-2ubuntu0.4) ...
    Selecting previously unselected package python3.5-venv.
    Preparing to unpack .../python3.5-venv_3.5.2-2ubuntu0~16.04.5_amd64.deb ...
    Unpacking python3.5-venv (3.5.2-2ubuntu0~16.04.5) ...
    Selecting previously unselected package python3-venv.
    Preparing to unpack .../python3-venv_3.5.1-3_amd64.deb ...
    Unpacking python3-venv (3.5.1-3) ...
    Processing triggers for libc-bin (2.23-0ubuntu10) ...
    Processing triggers for gnome-menus (3.13.3-6ubuntu3) ...
    Processing triggers for desktop-file-utils (0.22-1ubuntu5) ...
    Processing triggers for bamfdaemon (0.5.3~bzr0+16.04.20160415-0ubuntu1) ...
    Rebuilding /usr/share/applications/bamf-2.index...
    Processing triggers for mime-support (3.59ubuntu1) ...
    Processing triggers for man-db (2.7.5-1) ...
    Setting up libpython3.5-minimal:amd64 (3.5.2-2ubuntu0~16.04.5) ...
    Setting up libpython3.5-stdlib:amd64 (3.5.2-2ubuntu0~16.04.5) ...
    Setting up libpython3.5:amd64 (3.5.2-2ubuntu0~16.04.5) ...
    Setting up python3.5-minimal (3.5.2-2ubuntu0~16.04.5) ...
    Setting up python3.5 (3.5.2-2ubuntu0~16.04.5) ...
    Setting up python-pip-whl (8.1.1-2ubuntu0.4) ...
    Setting up python3.5-venv (3.5.2-2ubuntu0~16.04.5) ...
    Setting up python3-venv (3.5.1-3) ...
    Processing triggers for libc-bin (2.23-0ubuntu10) ...
    csk@csk-ai-revolution:~$ python3 -m venv env
    csk@csk-ai-revolution:~$ env/bin/python -m pip install --upgrade pip setuptools wheel
    Collecting pip
      Downloading https://files.pythonhosted.org/packages/c2/d7/90f34cb0d83a6c5631cf71dfe64cc1054598c843a92b400e55675cc2ac37/pip-18.1-py2.py3-none-any.whl (1.3MB)
        100% |████████████████████████████████| 1.3MB 134kB/s 
    Collecting setuptools
      Downloading https://files.pythonhosted.org/packages/37/06/754589caf971b0d2d48f151c2586f62902d93dc908e2fd9b9b9f6aa3c9dd/setuptools-40.6.3-py2.py3-none-any.whl (573kB)
        100% |████████████████████████████████| 573kB 1.1MB/s 
    Collecting wheel
      Downloading https://files.pythonhosted.org/packages/ff/47/1dfa4795e24fd6f93d5d58602dd716c3f101cfd5a77cd9acbe519b44a0a9/wheel-0.32.3-py2.py3-none-any.whl
    Installing collected packages: pip, setuptools, wheel
      Found existing installation: pip 8.1.1
        Uninstalling pip-8.1.1:
          Successfully uninstalled pip-8.1.1
      Found existing installation: setuptools 20.7.0
        Uninstalling setuptools-20.7.0:
          Successfully uninstalled setuptools-20.7.0
    Successfully installed pip-18.1 setuptools-40.6.3 wheel-0.32.3
    csk@csk-ai-revolution:~$ source env/bin/activate
    (env) csk@csk-ai-revolution:~$ sudo apt-get install portaudio19-dev libffi-dev libssl-dev
    Reading package lists... Done
    Building dependency tree       
    Reading state information... Done
    The following additional packages will be installed:
      libasound2-dev libjack-dev libjack0 libportaudiocpp0 libssl-doc libssl1.0.0
      libuuid1 uuid-dev zlib1g zlib1g-dev
    Suggested packages:
      libasound2-doc jackd1 portaudio19-doc
    The following packages will be REMOVED:
      libjack-jackd2-0
    The following NEW packages will be installed:
      libasound2-dev libffi-dev libjack-dev libjack0 libportaudiocpp0 libssl-dev
      libssl-doc portaudio19-dev uuid-dev zlib1g-dev
    The following packages will be upgraded:
      libssl1.0.0 libuuid1 zlib1g
    3 upgraded, 10 newly installed, 1 to remove and 560 not upgraded.
    Need to get 4,403 kB of archives.
    After this operation, 14.1 MB of additional disk space will be used.
    Do you want to continue? [Y/n] Y
    Get:1 http://archive.ubuntu.com/ubuntu xenial/universe amd64 libjack0 amd64 1:0.124.1+20140122git5013bed0-3build2 [43.1 kB]
    Get:2 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 libuuid1 amd64 2.27.1-6ubuntu3.6 [15.1 kB]
    Get:3 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 zlib1g amd64 1:1.2.8.dfsg-2ubuntu4.1 [51.2 kB]
    Get:4 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 libssl1.0.0 amd64 1.0.2g-1ubuntu4.14 [1,085 kB]
    Get:5 http://archive.ubuntu.com/ubuntu xenial/main amd64 libasound2-dev amd64 1.1.0-0ubuntu1 [114 kB]
    Get:6 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 uuid-dev amd64 2.27.1-6ubuntu3.6 [26.4 kB]
    Get:7 http://archive.ubuntu.com/ubuntu xenial/universe amd64 libjack-dev amd64 1:0.124.1+20140122git5013bed0-3build2 [199 kB]
    Get:8 http://archive.ubuntu.com/ubuntu xenial/main amd64 libportaudiocpp0 amd64 19+svn20140130-1build1 [15.4 kB]
    Get:9 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 zlib1g-dev amd64 1:1.2.8.dfsg-2ubuntu4.1 [168 kB]
    Get:10 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 libssl-dev amd64 1.0.2g-1ubuntu4.14 [1,345 kB]
    Get:11 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 libssl-doc all 1.0.2g-1ubuntu4.14 [1,078 kB]
    Get:12 http://archive.ubuntu.com/ubuntu xenial/main amd64 portaudio19-dev amd64 19+svn20140130-1build1 [102 kB]
    Get:13 http://archive.ubuntu.com/ubuntu xenial/main amd64 libffi-dev amd64 3.2.1-4 [161 kB]
    Fetched 4,403 kB in 1min 30s (48.9 kB/s)                                       
    Preconfiguring packages ...
    dpkg: libjack-jackd2-0:amd64: dependency problems, but removing anyway as you requested:
     gstreamer1.0-plugins-good:amd64 depends on libjack-jackd2-0 (>= 1.9.5~dfsg-14) | libjack-0.116; however:
      Package libjack-jackd2-0:amd64 is to be removed.
      Package libjack-0.116 is not installed.
      Package libjack-jackd2-0:amd64 which provides libjack-0.116 is to be removed.
     libasound2-plugins:amd64 depends on libjack-jackd2-0 (>= 1.9.5~dfsg-14) | libjack-0.116; however:
      Package libjack-jackd2-0:amd64 is to be removed.
      Package libjack-0.116 is not installed.
      Package libjack-jackd2-0:amd64 which provides libjack-0.116 is to be removed.
     libportaudio2:amd64 depends on libjack-jackd2-0 (>= 1.9.5~dfsg-14) | libjack-0.116; however:
      Package libjack-jackd2-0:amd64 is to be removed.
      Package libjack-0.116 is not installed.
      Package libjack-jackd2-0:amd64 which provides libjack-0.116 is to be removed.
     gstreamer1.0-plugins-good:amd64 depends on libjack-jackd2-0 (>= 1.9.5~dfsg-14) | libjack-0.116; however:
      Package libjac
    (Reading database ... 215618 files and directories currently installed.)
    Removing libjack-jackd2-0:amd64 (1.9.10+20150825git1ed50c92~dfsg-1ubuntu1) ...
    Processing triggers for libc-bin (2.23-0ubuntu10) ...
    Selecting previously unselected package libjack0:amd64.
    (Reading database ... 215609 files and directories currently installed.)
    Preparing to unpack .../libjack0_1%3a0.124.1+20140122git5013bed0-3build2_amd64.deb ...
    Unpacking libjack0:amd64 (1:0.124.1+20140122git5013bed0-3build2) ...
    Preparing to unpack .../libuuid1_2.27.1-6ubuntu3.6_amd64.deb ...
    Unpacking libuuid1:amd64 (2.27.1-6ubuntu3.6) over (2.27.1-6ubuntu3) ...
    Processing triggers for libc-bin (2.23-0ubuntu10) ...
    Setting up libuuid1:amd64 (2.27.1-6ubuntu3.6) ...
    Processing triggers for libc-bin (2.23-0ubuntu10) ...
    (Reading database ... 215618 files and directories currently installed.)
    Preparing to unpack .../zlib1g_1%3a1.2.8.dfsg-2ubuntu4.1_amd64.deb ...
    Unpacking zlib1g:amd64 (1:1.2.8.dfsg-2ubuntu4.1) over (1:1.2.8.dfsg-2ubuntu4) ...
    Processing triggers for libc-bin (2.23-0ubuntu10) ...
    Setting up zlib1g:amd64 (1:1.2.8.dfsg-2ubuntu4.1) ...
    Processing triggers for libc-bin (2.23-0ubuntu10) ...
    (Reading database ... 215618 files and directories currently installed.)
    Preparing to unpack .../libssl1.0.0_1.0.2g-1ubuntu4.14_amd64.deb ...
    Unpacking libssl1.0.0:amd64 (1.0.2g-1ubuntu4.14) over (1.0.2g-1ubuntu4.13) ...
    Selecting previously unselected package libasound2-dev:amd64.
    Preparing to unpack .../libasound2-dev_1.1.0-0ubuntu1_amd64.deb ...
    Unpacking libasound2-dev:amd64 (1.1.0-0ubuntu1) ...
    Selecting previously unselected package uuid-dev:amd64.
    Preparing to unpack .../uuid-dev_2.27.1-6ubuntu3.6_amd64.deb ...
    Unpacking uuid-dev:amd64 (2.27.1-6ubuntu3.6) ...
    Selecting previously unselected package libjack-dev.
    Preparing to unpack .../libjack-dev_1%3a0.124.1+20140122git5013bed0-3build2_amd64.deb ...
    Unpacking libjack-dev (1:0.124.1+20140122git5013bed0-3build2) ...
    Selecting previously unselected package libportaudiocpp0:amd64.
    Preparing to unpack .../libportaudiocpp0_19+svn20140130-1build1_amd64.deb ...
    Unpacking libportaudiocpp0:amd64 (19+svn20140130-1build1) ...
    Selecting previously unselected package zlib1g-dev:amd64.
    Preparing to unpack .../zlib1g-dev_1%3a1.2.8.dfsg-2ubuntu4.1_amd64.deb ...
    Unpacking zlib1g-dev:amd64 (1:1.2.8.dfsg-2ubuntu4.1) ...
    Selecting previously unselected package libssl-dev:amd64.
    Preparing to unpack .../libssl-dev_1.0.2g-1ubuntu4.14_amd64.deb ...
    Unpacking libssl-dev:amd64 (1.0.2g-1ubuntu4.14) ...
    Selecting previously unselected package libssl-doc.
    Preparing to unpack .../libssl-doc_1.0.2g-1ubuntu4.14_all.deb ...
    Unpacking libssl-doc (1.0.2g-1ubuntu4.14) ...
    Selecting previously unselected package portaudio19-dev.
    Preparing to unpack .../portaudio19-dev_19+svn20140130-1build1_amd64.deb ...
    Unpacking portaudio19-dev (19+svn20140130-1build1) ...
    Selecting previously unselected package libffi-dev:amd64.
    Preparing to unpack .../libffi-dev_3.2.1-4_amd64.deb ...
    Unpacking libffi-dev:amd64 (3.2.1-4) ...
    Processing triggers for libc-bin (2.23-0ubuntu10) ...
    Processing triggers for man-db (2.7.5-1) ...
    Processing triggers for doc-base (0.10.7) ...
    Processing 2 added doc-base files...
    Processing triggers for install-info (6.1.0.dfsg.1-5) ...
    Setting up libjack0:amd64 (1:0.124.1+20140122git5013bed0-3build2) ...
    Setting up libssl1.0.0:amd64 (1.0.2g-1ubuntu4.14) ...
    Setting up libasound2-dev:amd64 (1.1.0-0ubuntu1) ...
    Setting up uuid-dev:amd64 (2.27.1-6ubuntu3.6) ...
    Setting up libjack-dev (1:0.124.1+20140122git5013bed0-3build2) ...
    Setting up libportaudiocpp0:amd64 (19+svn20140130-1build1) ...
    Setting up zlib1g-dev:amd64 (1:1.2.8.dfsg-2ubuntu4.1) ...
    Setting up libssl-dev:amd64 (1.0.2g-1ubuntu4.14) ...
    Setting up libssl-doc (1.0.2g-1ubuntu4.14) ...
    Setting up portaudio19-dev (19+svn20140130-1build1) ...
    Setting up libffi-dev:amd64 (3.2.1-4) ...
    Processing triggers for libc-bin (2.23-0ubuntu10) ...
    (env) csk@csk-ai-revolution:~$ python -m pip install --upgrade google-assistant-sdk[samples]
    Collecting google-assistant-sdk[samples]
      Downloading https://files.pythonhosted.org/packages/63/1d/c161b38a4e7ce72edcf78aab725dcb07047c13e17dacede142931159adb4/google_assistant_sdk-0.5.0-py2.py3-none-any.whl
    Collecting google-auth-oauthlib[tool]>=0.1.0 (from google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/46/df/d1f94ee2cffe5a83721f262efe51f3b2dcdd3b616caf007b8490e824c550/google_auth_oauthlib-0.2.0-py2.py3-none-any.whl
    Collecting google-assistant-grpc==0.2.0; extra == "samples" (from google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/d3/3c/4a44b54b196fb7f23335f17fdfd3ce477cbff2404324df2ef9ef1f3e4bd3/google_assistant_grpc-0.2.0-py2.py3-none-any.whl
    Collecting tenacity<5,>=4.1.0; extra == "samples" (from google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/75/1b/46a6a7b7c2b16811665ea09b7e63e7e6b7f9b5dedf2d0ba67e029668403c/tenacity-4.12.0-py2.py3-none-any.whl
    Collecting sounddevice<0.4,>=0.3.7; extra == "samples" (from google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/db/47/c4da7ae5dd111f8031f28d55d08f3f226515463ba739e6a4360a00c8cb5b/sounddevice-0.3.12-py2.py3-none-any.whl
    Collecting click<7,>=6.7; extra == "samples" (from google-assistant-sdk[samples])
      Using cached https://files.pythonhosted.org/packages/34/c1/8806f99713ddb993c5366c362b2f908f18269f8d792aff1abfd700775a77/click-6.7-py2.py3-none-any.whl
    Collecting urllib3[secure]<2,>=1.21; extra == "samples" (from google-assistant-sdk[samples])
      Using cached https://files.pythonhosted.org/packages/62/00/ee1d7de624db8ba7090d1226aebefab96a2c71cd5cfa7629d6ad3f61b79e/urllib3-1.24.1-py2.py3-none-any.whl
    Collecting futures<4,>=3.1.1; extra == "samples" (from google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/cc/26/b61e3a4eb50653e8a7339d84eeaa46d1e93b92951978873c220ae64d0733/futures-3.1.1.tar.gz
    Collecting pathlib2<3,>=2.3.0; extra == "samples" (from google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/2a/46/c696dcf1c7aad917b39b875acdc5451975e3a9b4890dca8329983201c97a/pathlib2-2.3.3-py2.py3-none-any.whl
    Collecting google-auth (from google-auth-oauthlib[tool]>=0.1.0->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/4e/85/71b2dfbf5b4241cd031cc333ed71f90a271074a97cb2c517bb65f07a1a90/google_auth-1.6.2-py2.py3-none-any.whl (73kB)
        100% |████████████████████████████████| 81kB 1.5MB/s 
    Collecting requests-oauthlib>=0.7.0 (from google-auth-oauthlib[tool]>=0.1.0->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/94/e7/c250d122992e1561690d9c0f7856dadb79d61fd4bdd0e598087dce607f6c/requests_oauthlib-1.0.0-py2.py3-none-any.whl
    Collecting grpcio>=1.3.5 (from google-assistant-grpc==0.2.0; extra == "samples"->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/d9/94/7c634ccc859169ceebca7140532b5267a0b0ed5583e1e624663997786895/grpcio-1.17.1-cp35-cp35m-manylinux1_x86_64.whl (10.1MB)
        100% |████████████████████████████████| 10.1MB 1.1MB/s 
    Collecting googleapis-common-protos>=1.5.2 (from google-assistant-grpc==0.2.0; extra == "samples"->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/ae/94/a256572abf5d10347301c638d5df552fab1515497270726e6b56698d2e99/googleapis-common-protos-1.5.5.tar.gz
    Collecting six>=1.9.0 (from tenacity<5,>=4.1.0; extra == "samples"->google-assistant-sdk[samples])
      Using cached https://files.pythonhosted.org/packages/73/fb/00a976f728d0d1fecfe898238ce23f502a721c0ac0ecfedb80e0d88c64e9/six-1.12.0-py2.py3-none-any.whl
    Collecting CFFI>=1.0 (from sounddevice<0.4,>=0.3.7; extra == "samples"->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/59/cc/0e1635b4951021ef35f5c92b32c865ae605fac2a19d724fb6ff99d745c81/cffi-1.11.5-cp35-cp35m-manylinux1_x86_64.whl (420kB)
        100% |████████████████████████████████| 430kB 1.4MB/s 
    Collecting cryptography>=1.3.4; extra == "secure" (from urllib3[secure]<2,>=1.21; extra == "samples"->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/60/c7/99b33c53cf3f20a97a4c4bfd3ab66dcc93d99da0a97cc9597aa36ae6bb62/cryptography-2.4.2-cp34-abi3-manylinux1_x86_64.whl (2.1MB)
        100% |████████████████████████████████| 2.1MB 351kB/s 
    Collecting certifi; extra == "secure" (from urllib3[secure]<2,>=1.21; extra == "samples"->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/9f/e0/accfc1b56b57e9750eba272e24c4dddeac86852c2bebd1236674d7887e8a/certifi-2018.11.29-py2.py3-none-any.whl (154kB)
        100% |████████████████████████████████| 163kB 734kB/s 
    Collecting pyOpenSSL>=0.14; extra == "secure" (from urllib3[secure]<2,>=1.21; extra == "samples"->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/96/af/9d29e6bd40823061aea2e0574ccb2fcf72bfd6130ce53d32773ec375458c/pyOpenSSL-18.0.0-py2.py3-none-any.whl (53kB)
        100% |████████████████████████████████| 61kB 1.2MB/s 
    Collecting ipaddress; extra == "secure" (from urllib3[secure]<2,>=1.21; extra == "samples"->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/fc/d0/7fc3a811e011d4b388be48a0e381db8d990042df54aa4ef4599a31d39853/ipaddress-1.0.22-py2.py3-none-any.whl
    Collecting idna>=2.0.0; extra == "secure" (from urllib3[secure]<2,>=1.21; extra == "samples"->google-assistant-sdk[samples])
      Using cached https://files.pythonhosted.org/packages/14/2c/cd551d81dbe15200be1cf41cd03869a46fe7226e7450af7a6545bfc474c9/idna-2.8-py2.py3-none-any.whl
    Collecting rsa>=3.1.4 (from google-auth->google-auth-oauthlib[tool]>=0.1.0->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/02/e5/38518af393f7c214357079ce67a317307936896e961e35450b70fad2a9cf/rsa-4.0-py2.py3-none-any.whl
    Collecting pyasn1-modules>=0.2.1 (from google-auth->google-auth-oauthlib[tool]>=0.1.0->google-assistant-sdk[samples])
      Using cached https://files.pythonhosted.org/packages/19/02/fa63f7ba30a0d7b925ca29d034510fc1ffde53264b71b4155022ddf3ab5d/pyasn1_modules-0.2.2-py2.py3-none-any.whl
    Collecting cachetools>=2.0.0 (from google-auth->google-auth-oauthlib[tool]>=0.1.0->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/76/7e/08cd3846bebeabb6b1cfc4af8aae649d90249b4aeed080bddb5297f1d73b/cachetools-3.0.0-py2.py3-none-any.whl
    Collecting requests>=2.0.0 (from requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]>=0.1.0->google-assistant-sdk[samples])
      Using cached https://files.pythonhosted.org/packages/7d/e3/20f3d364d6c8e5d2353c72a67778eb189176f08e873c9900e10c0287b84b/requests-2.21.0-py2.py3-none-any.whl
    Collecting oauthlib>=0.6.2 (from requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]>=0.1.0->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/e6/d1/ddd9cfea3e736399b97ded5c2dd62d1322adef4a72d816f1ed1049d6a179/oauthlib-2.1.0-py2.py3-none-any.whl (121kB)
        100% |████████████████████████████████| 122kB 52kB/s 
    Collecting protobuf>=3.0.0 (from googleapis-common-protos>=1.5.2->google-assistant-grpc==0.2.0; extra == "samples"->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/bf/d4/db7296a1407cad69f043537ba1e05afab3646451a066ead7a314d8714388/protobuf-3.6.1-cp35-cp35m-manylinux1_x86_64.whl (1.1MB)
        100% |████████████████████████████████| 1.1MB 56kB/s 
    Collecting pycparser (from CFFI>=1.0->sounddevice<0.4,>=0.3.7; extra == "samples"->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/68/9e/49196946aee219aead1290e00d1e7fdeab8567783e83e1b9ab5585e6206a/pycparser-2.19.tar.gz (158kB)
        100% |████████████████████████████████| 163kB 487kB/s 
    Collecting asn1crypto>=0.21.0 (from cryptography>=1.3.4; extra == "secure"->urllib3[secure]<2,>=1.21; extra == "samples"->google-assistant-sdk[samples])
      Downloading https://files.pythonhosted.org/packages/ea/cd/35485615f45f30a510576f1a56d1e0a7ad7bd8ab5ed7cdc600ef7cd06222/asn1crypto-0.24.0-py2.py3-none-any.whl (101kB)
        100% |████████████████████████████████| 102kB 557kB/s 
    Collecting pyasn1>=0.1.3 (from rsa>=3.1.4->google-auth->google-auth-oauthlib[tool]>=0.1.0->google-assistant-sdk[samples])
      Using cached https://files.pythonhosted.org/packages/d1/a1/7790cc85db38daa874f6a2e6308131b9953feb1367f2ae2d1123bb93a9f5/pyasn1-0.4.4-py2.py3-none-any.whl
    Collecting chardet<3.1.0,>=3.0.2 (from requests>=2.0.0->requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]>=0.1.0->google-assistant-sdk[samples])
      Using cached https://files.pythonhosted.org/packages/bc/a9/01ffebfb562e4274b6487b4bb1ddec7ca55ec7510b22e4c51f14098443b8/chardet-3.0.4-py2.py3-none-any.whl
    Requirement already satisfied, skipping upgrade: setuptools in ./env/lib/python3.5/site-packages (from protobuf>=3.0.0->googleapis-common-protos>=1.5.2->google-assistant-grpc==0.2.0; extra == "samples"->google-assistant-sdk[samples]) (40.6.3)
    Building wheels for collected packages: futures, googleapis-common-protos, pycparser
      Running setup.py bdist_wheel for futures ... done
      Stored in directory: /home/csk/.cache/pip/wheels/f3/f9/c7/4fbf1faa6038faf183f6e3ea61f17a5f7eea5ab9a1dd7753fd
      Running setup.py bdist_wheel for googleapis-common-protos ... done
      Stored in directory: /home/csk/.cache/pip/wheels/22/57/2c/fdf1a5d9f14360bd1123c6dbac26eb784eba25223800239a69
      Running setup.py bdist_wheel for pycparser ... done
      Stored in directory: /home/csk/.cache/pip/wheels/f2/9a/90/de94f8556265ddc9d9c8b271b0f63e57b26fb1d67a45564511
    Successfully built futures googleapis-common-protos pycparser
    Installing collected packages: pyasn1, rsa, pyasn1-modules, cachetools, six, google-auth, idna, asn1crypto, pycparser, CFFI, cryptography, certifi, pyOpenSSL, ipaddress, urllib3, chardet, requests, oauthlib, requests-oauthlib, click, google-auth-oauthlib, grpcio, protobuf, googleapis-common-protos, google-assistant-grpc, tenacity, sounddevice, futures, pathlib2, google-assistant-sdk
    Successfully installed CFFI-1.11.5 asn1crypto-0.24.0 cachetools-3.0.0 certifi-2018.11.29 chardet-3.0.4 click-6.7 cryptography-2.4.2 futures-3.1.1 google-assistant-grpc-0.2.0 google-assistant-sdk-0.5.0 google-auth-1.6.2 google-auth-oauthlib-0.2.0 googleapis-common-protos-1.5.5 grpcio-1.17.1 idna-2.8 ipaddress-1.0.22 oauthlib-2.1.0 pathlib2-2.3.3 protobuf-3.6.1 pyOpenSSL-18.0.0 pyasn1-0.4.4 pyasn1-modules-0.2.2 pycparser-2.19 requests-2.21.0 requests-oauthlib-1.0.0 rsa-4.0 six-1.12.0 sounddevice-0.3.12 tenacity-4.12.0 urllib3-1.24.1
    (env) csk@csk-ai-revolution:~$ python -m pip install grpcio
    Requirement already satisfied: grpcio in ./env/lib/python3.5/site-packages (1.17.1)
    Requirement already satisfied: six>=1.5.2 in ./env/lib/python3.5/site-packages (from grpcio) (1.12.0)
    (env) csk@csk-ai-revolution:~$ git clone https://github.com/googleapis/googleapis.git
    Cloning into 'googleapis'...
    remote: Enumerating objects: 425, done.
    remote: Counting objects: 100% (425/425), done.
    remote: Compressing objects: 100% (116/116), done.
    (env) csk@csk-ai-revolution:~$ python -m pip install --upgrade google-auth-oauthlib[tool]
    Requirement already up-to-date: google-auth-oauthlib[tool] in ./env/lib/python3.5/site-packages (0.2.0)
    Requirement already satisfied, skipping upgrade: requests-oauthlib>=0.7.0 in ./env/lib/python3.5/site-packages (from google-auth-oauthlib[tool]) (1.0.0)
    Requirement already satisfied, skipping upgrade: google-auth in ./env/lib/python3.5/site-packages (from google-auth-oauthlib[tool]) (1.6.2)
    Requirement already satisfied, skipping upgrade: click; extra == "tool" in ./env/lib/python3.5/site-packages (from google-auth-oauthlib[tool]) (6.7)
    Requirement already satisfied, skipping upgrade: oauthlib>=0.6.2 in ./env/lib/python3.5/site-packages (from requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]) (2.1.0)
    Requirement already satisfied, skipping upgrade: requests>=2.0.0 in ./env/lib/python3.5/site-packages (from requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]) (2.21.0)
    Requirement already satisfied, skipping upgrade: pyasn1-modules>=0.2.1 in ./env/lib/python3.5/site-packages (from google-auth->google-auth-oauthlib[tool]) (0.2.2)
    Requirement already satisfied, skipping upgrade: cachetools>=2.0.0 in ./env/lib/python3.5/site-packages (from google-auth->google-auth-oauthlib[tool]) (3.0.0)
    Requirement already satisfied, skipping upgrade: rsa>=3.1.4 in ./env/lib/python3.5/site-packages (from google-auth->google-auth-oauthlib[tool]) (4.0)
    Requirement already satisfied, skipping upgrade: six>=1.9.0 in ./env/lib/python3.5/site-packages (from google-auth->google-auth-oauthlib[tool]) (1.12.0)
    Requirement already satisfied, skipping upgrade: chardet<3.1.0,>=3.0.2 in ./env/lib/python3.5/site-packages (from requests>=2.0.0->requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]) (3.0.4)
    Requirement already satisfied, skipping upgrade: idna<2.9,>=2.5 in ./env/lib/python3.5/site-packages (from requests>=2.0.0->requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]) (2.8)
    Requirement already satisfied, skipping upgrade: urllib3<1.25,>=1.21.1 in ./env/lib/python3.5/site-packages (from requests>=2.0.0->requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]) (1.24.1)
    Requirement already satisfied, skipping upgrade: certifi>=2017.4.17 in ./env/lib/python3.5/site-packages (from requests>=2.0.0->requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]) (2018.11.29)
    Requirement already satisfied, skipping upgrade: pyasn1<0.5.0,>=0.4.1 in ./env/lib/python3.5/site-packages (from pyasn1-modules>=0.2.1->google-auth->google-auth-oauthlib[tool]) (0.4.4)
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --scope https://www.googleapis.com/auth/assistant-sdk-prototype \
    >       --save --headless --client-secrets client_secret_client-id.json
    Traceback (most recent call last):
      File "/home/csk/env/bin/google-oauthlib-tool", line 11, in <module>
        sys.exit(main())
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 722, in __call__
        return self.main(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 697, in main
        rv = self.invoke(ctx)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 895, in invoke
        return ctx.invoke(self.callback, **ctx.params)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 535, in invoke
        return callback(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/tool/__main__.py", line 100, in main
        scopes=scope
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 171, in from_client_secrets_file
        with open(client_secrets_file, 'r') as json_file:
    FileNotFoundError: [Errno 2] No such file or directory: 'client_secret_client-id.json'
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --scope https://www.googleapis.com/auth/assistant-sdk-prototype       --save --headless --client-secrets /client_secret_client-id.json
    Traceback (most recent call last):
      File "/home/csk/env/bin/google-oauthlib-tool", line 11, in <module>
        sys.exit(main())
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 722, in __call__
        return self.main(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 697, in main
        rv = self.invoke(ctx)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 895, in invoke
        return ctx.invoke(self.callback, **ctx.params)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 535, in invoke
        return callback(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/tool/__main__.py", line 100, in main
        scopes=scope
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 171, in from_client_secrets_file
        with open(client_secrets_file, 'r') as json_file:
    FileNotFoundError: [Errno 2] No such file or directory: '/client_secret_client-id.json'
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --scope https://www.googleapis.com/auth/assistant-sdk-prototype       --save --headless --client-secrets 
    31131036_1657332284322369_6524597261597409280_o.jpg  .ipython/                                            .profile
    anaconda/                                            .java/                                               Public/
    .astropy/                                            java_error_in_PYCHARM_2068.log                       .PyCharmCE2018.2/
    .bash_history                                        java_error_in_PYCHARM_2348.log                       PycharmProjects/
    .bash_logout                                         java_error_in_PYCHARM_2362.log                       .python_history
    .bashrc                                              java_error_in_PYCHARM_2420.log                       Python_Instrction_manual.odt
    .cache/                                              java_error_in_PYCHARM_2447.log                       sample.mwb
    .conda/                                              java_error_in_PYCHARM_3366.log                       sample.mwb.bak
    .config/                                             java_error_in_PYCHARM_3671.log                       Sathish/
    Desktop/                                             java_error_in_PYCHARM_3732.log                       SmartBear/
    .dmrc                                                java_error_in_PYCHARM.hprof                          .soapuios/
    Documents/                                           .jupyter/                                            SoapUI-Tutorials/
    Downloads/                                           .keras/                                              .ssh/
    DSC_2908.JPG                                         .local/                                              .sudo_as_admin_successful
    .eclipse/                                            .~lock.Python_Instrction_manual.odt#                 .swt/
    eclipse-workspace/                                   .luminoth/                                           table_detection_dl/
    env/                                                 .mozilla/                                            Templates/
    examples.desktop                                     Music/                                               .thunderbird/
    .gconf/                                              .mysql/                                              .tooling/
    .gitconfig                                           .nano/                                               Videos/
    .gnome/                                              .oracle_jre_usage/                                   .Xauthority
    .gnupg/                                              .p2/                                                 .xsession-errors
    .ICEauthority                                        Pictures/                                            .xsession-errors.old
    .install4j                                           .pki/                                                
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --scope https://www.googleapis.com/auth/assistant-sdk-prototype       --save --headless --client-secrets /home/csk/
    31131036_1657332284322369_6524597261597409280_o.jpg  .ipython/                                            .profile
    anaconda/                                            .java/                                               Public/
    .astropy/                                            java_error_in_PYCHARM_2068.log                       .PyCharmCE2018.2/
    .bash_history                                        java_error_in_PYCHARM_2348.log                       PycharmProjects/
    .bash_logout                                         java_error_in_PYCHARM_2362.log                       .python_history
    .bashrc                                              java_error_in_PYCHARM_2420.log                       Python_Instrction_manual.odt
    .cache/                                              java_error_in_PYCHARM_2447.log                       sample.mwb
    .conda/                                              java_error_in_PYCHARM_3366.log                       sample.mwb.bak
    .config/                                             java_error_in_PYCHARM_3671.log                       Sathish/
    Desktop/                                             java_error_in_PYCHARM_3732.log                       SmartBear/
    .dmrc                                                java_error_in_PYCHARM.hprof                          .soapuios/
    Documents/                                           .jupyter/                                            SoapUI-Tutorials/
    Downloads/                                           .keras/                                              .ssh/
    DSC_2908.JPG                                         .local/                                              .sudo_as_admin_successful
    .eclipse/                                            .~lock.Python_Instrction_manual.odt#                 .swt/
    eclipse-workspace/                                   .luminoth/                                           table_detection_dl/
    env/                                                 .mozilla/                                            Templates/
    examples.desktop                                     Music/                                               .thunderbird/
    .gconf/                                              .mysql/                                              .tooling/
    .gitconfig                                           .nano/                                               Videos/
    .gnome/                                              .oracle_jre_usage/                                   .Xauthority
    .gnupg/                                              .p2/                                                 .xsession-errors
    .ICEauthority                                        Pictures/                                            .xsession-errors.old
    .install4j                                           .pki/                                                
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --scope https://www.googleapis.com/auth/assistant-sdk-prototype       --save --headless --client-secrets /home/csk/D
    Desktop/      Documents/    Downloads/    DSC_2908.JPG  
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --scope https://www.googleapis.com/auth/assistant-sdk-prototype       --save --headless --client-secrets /home/csk/Downloads/
    Algo_ver2.docx                                           mysql-8.0.12-linux-glibc2.12-x86_64.tar (1).xz
    Anaconda3-5.2.0-Linux-x86_64.sh                          mysql-8.0.12-linux-glibc2.12-x86_64.tar.xz
    beginners_python_cheat_sheet_pcc_all.pdf                 mysql-apt-config_0.8.10-1_all (1).deb
    cryptography_mp4.ipynb                                   mysql-apt-config_0.8.10-1_all.deb
    data/                                                    mysql-test-8.0.12-linux-glibc2.12-x86_64.tar.xz
    data.zip                                                 mysql-workbench-community_8.0.12-1ubuntu18.04_amd64.deb
    eclipse/                                                 out.avi
    eclipse-jee-2018-09-linux-gtk-x86_64.tar.gz              own_project_doc2vec.py
    Falls9.mov                                               pycharm-community-2018.2/
    firefox-62.0.2.tar.bz2                                   pycharm-community-2018.2.tar.gz
    glove.6B.100d.txt.zip                                    SampleVideo_1280x720_1mb (1).mp4
    google-chrome-stable_current_amd64 (1).deb               skypeforlinux-64.deb
    google-chrome-stable_current_amd64.deb                   skypeforlinux-64.rpm
    image_cryptograpy-master.zip                             SoapUI-x64-5.4.0.sh
    jdk1.8.0_181/                                            sp87428.exe
    jdk-8u181-linux-x64.rpm                                  swift-4.1.3-RELEASE-ubuntu14.04/
    jdk-8u181-linux-x64.tar.gz                               swift-4.1.3-RELEASE-ubuntu14.04 (1).tar.gz
    LM-LSTM-CRF-master/                                      swift-4.1.3-RELEASE-ubuntu14.04.tar.gz
    LM-LSTM-CRF-master.zip                                   transcripts.csv
    .~lock.Algo_ver2.docx#                                   video.mp4
    My Project 36579-d6893ec94393.json                       videoplayback (1).mp4
    mysql-8.0.12-linux-glibc2.12-x86_64.tar                  videoplayback (2).mp4
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --scope https://www.googleapis.com/auth/assistant-sdk-prototype       --save --headless --client-secrets /home/csk/Downloads/My\ Project\ 36579-d6893ec94393.json 
    Traceback (most recent call last):
      File "/home/csk/env/bin/google-oauthlib-tool", line 11, in <module>
        sys.exit(main())
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 722, in __call__
        return self.main(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 697, in main
        rv = self.invoke(ctx)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 895, in invoke
        return ctx.invoke(self.callback, **ctx.params)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 535, in invoke
        return callback(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/tool/__main__.py", line 100, in main
        scopes=scope
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 174, in from_client_secrets_file
        return cls.from_client_config(client_config, scopes=scopes, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 147, in from_client_config
        'Client secrets must be for a web or installed app.')
    ValueError: Client secrets must be for a web or installed app.
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/ --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless31131036_1657332284322369_6524597261597409280_o.jpg  .ipython/                                            .profile
    anaconda/                                            .java/                                               Public/
    .astropy/                                            java_error_in_PYCHARM_2068.log                       .PyCharmCE2018.2/
    .bash_history                                        java_error_in_PYCHARM_2348.log                       PycharmProjects/
    .bash_logout                                         java_error_in_PYCHARM_2362.log                       .python_history
    .bashrc                                              java_error_in_PYCHARM_2420.log                       Python_Instrction_manual.odt
    .cache/                                              java_error_in_PYCHARM_2447.log                       sample.mwb
    .conda/                                              java_error_in_PYCHARM_3366.log                       sample.mwb.bak
    .config/                                             java_error_in_PYCHARM_3671.log                       Sathish/
    Desktop/                                             java_error_in_PYCHARM_3732.log                       SmartBear/
    .dmrc                                                java_error_in_PYCHARM.hprof                          .soapuios/
    Documents/                                           .jupyter/                                            SoapUI-Tutorials/
    Downloads/                                           .keras/                                              .ssh/
    DSC_2908.JPG                                         .local/                                              .sudo_as_admin_successful
    .eclipse/                                            .~lock.Python_Instrction_manual.odt#                 .swt/
    eclipse-workspace/                                   .luminoth/                                           table_detection_dl/
    env/                                                 .mozilla/                                            Templates/
    examples.desktop                                     Music/                                               .thunderbird/
    .gconf/                                              .mysql/                                              .tooling/
    .gitconfig                                           .nano/                                               Videos/
    .gnome/                                              .oracle_jre_usage/                                   .Xauthority
    .gnupg/                                              .p2/                                                 .xsession-errors
    .ICEauthority                                        Pictures/                                            .xsession-errors.old
    .install4j                                           .pki/                                                
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/My\ Project\ 36579-d6893ec94393.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Traceback (most recent call last):
      File "/home/csk/env/bin/google-oauthlib-tool", line 11, in <module>
        sys.exit(main())
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 722, in __call__
        return self.main(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 697, in main
        rv = self.invoke(ctx)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 895, in invoke
        return ctx.invoke(self.callback, **ctx.params)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 535, in invoke
        return callback(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/tool/__main__.py", line 100, in main
        scopes=scope
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 174, in from_client_secrets_file
        return cls.from_client_config(client_config, scopes=scopes, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 147, in from_client_config
        'Client secrets must be for a web or installed app.')
    ValueError: Client secrets must be for a web or installed app.
    (env) csk@csk-ai-revolution:~$ ^C
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/c --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json
    cryptography_mp4.ipynb
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=NBCS2TrdssjzES7tv6s23tOReKZ5cQ&prompt=consent&access_type=offline
    Enter the authorization code: 
    Traceback (most recent call last):
      File "/home/csk/env/bin/google-oauthlib-tool", line 11, in <module>
        sys.exit(main())
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 722, in __call__
        return self.main(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 697, in main
        rv = self.invoke(ctx)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 895, in invoke
        return ctx.invoke(self.callback, **ctx.params)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 535, in invoke
        return callback(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/tool/__main__.py", line 106, in main
        creds = flow.run_console()
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 364, in run_console
        self.fetch_token(code=code)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 241, in fetch_token
        self.client_config['token_uri'], **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/requests_oauthlib/oauth2_session.py", line 192, in fetch_token
        raise ValueError('Please supply either code or '
    ValueError: Please supply either code or authorization_response parameters.
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=q5KlqU22qKqnP3S1IbnN73N4d7oL5Y&prompt=consent&access_type=offline
    Enter the authorization code: ww
    Traceback (most recent call last):
      File "/home/csk/env/lib/python3.5/site-packages/urllib3/contrib/pyopenssl.py", line 453, in wrap_socket
        cnx.do_handshake()
      File "/home/csk/env/lib/python3.5/site-packages/OpenSSL/SSL.py", line 1907, in do_handshake
        self._raise_ssl_error(self._ssl, result)
      File "/home/csk/env/lib/python3.5/site-packages/OpenSSL/SSL.py", line 1631, in _raise_ssl_error
        raise SysCallError(errno, errorcode.get(errno))
    OpenSSL.SSL.SysCallError: (104, 'ECONNRESET')
    
    During handling of the above exception, another exception occurred:
    
    Traceback (most recent call last):
      File "/home/csk/env/lib/python3.5/site-packages/urllib3/connectionpool.py", line 600, in urlopen
        chunked=chunked)
      File "/home/csk/env/lib/python3.5/site-packages/urllib3/connectionpool.py", line 343, in _make_request
        self._validate_conn(conn)
      File "/home/csk/env/lib/python3.5/site-packages/urllib3/connectionpool.py", line 839, in _validate_conn
        conn.connect()
      File "/home/csk/env/lib/python3.5/site-packages/urllib3/connection.py", line 344, in connect
        ssl_context=context)
      File "/home/csk/env/lib/python3.5/site-packages/urllib3/util/ssl_.py", line 344, in ssl_wrap_socket
        return context.wrap_socket(sock, server_hostname=server_hostname)
      File "/home/csk/env/lib/python3.5/site-packages/urllib3/contrib/pyopenssl.py", line 459, in wrap_socket
        raise ssl.SSLError('bad handshake: %r' % e)
    ssl.SSLError: ("bad handshake: SysCallError(104, 'ECONNRESET')",)
    
    During handling of the above exception, another exception occurred:
    
    Traceback (most recent call last):
      File "/home/csk/env/lib/python3.5/site-packages/requests/adapters.py", line 449, in send
        timeout=timeout
      File "/home/csk/env/lib/python3.5/site-packages/urllib3/connectionpool.py", line 638, in urlopen
        _stacktrace=sys.exc_info()[2])
      File "/home/csk/env/lib/python3.5/site-packages/urllib3/util/retry.py", line 398, in increment
        raise MaxRetryError(_pool, url, error or ResponseError(cause))
    urllib3.exceptions.MaxRetryError: HTTPSConnectionPool(host='accounts.google.com', port=443): Max retries exceeded with url: /o/oauth2/token (Caused by SSLError(SSLError("bad handshake: SysCallError(104, 'ECONNRESET')",),))
    
    During handling of the above exception, another exception occurred:
    
    Traceback (most recent call last):
      File "/home/csk/env/bin/google-oauthlib-tool", line 11, in <module>
        sys.exit(main())
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 722, in __call__
        return self.main(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 697, in main
        rv = self.invoke(ctx)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 895, in invoke
        return ctx.invoke(self.callback, **ctx.params)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 535, in invoke
        return callback(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/tool/__main__.py", line 106, in main
        creds = flow.run_console()
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 364, in run_console
        self.fetch_token(code=code)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 241, in fetch_token
        self.client_config['token_uri'], **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/requests_oauthlib/oauth2_session.py", line 221, in fetch_token
        verify=verify, proxies=proxies)
      File "/home/csk/env/lib/python3.5/site-packages/requests/sessions.py", line 581, in post
        return self.request('POST', url, data=data, json=json, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/requests_oauthlib/oauth2_session.py", line 360, in request
        headers=headers, data=data, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/requests/sessions.py", line 533, in request
        resp = self.send(prep, **send_kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/requests/sessions.py", line 646, in send
        r = adapter.send(request, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/requests/adapters.py", line 514, in send
        raise SSLError(e, request=request)
    requests.exceptions.SSLError: HTTPSConnectionPool(host='accounts.google.com', port=443): Max retries exceeded with url: /o/oauth2/token (Caused by SSLError(SSLError("bad handshake: SysCallError(104, 'ECONNRESET')",),))
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=VdGg1nkJYzU7WmKy9aaVqziaodNJrK&access_type=offline&prompt=consent
    Enter the authorization code: ^C
    Aborted!
    (env) csk@csk-ai-revolution:~$ pip install --upgrade google-auth-oauthlib[tool]
    Requirement already up-to-date: google-auth-oauthlib[tool] in ./env/lib/python3.5/site-packages (0.2.0)
    Requirement already satisfied, skipping upgrade: google-auth in ./env/lib/python3.5/site-packages (from google-auth-oauthlib[tool]) (1.6.2)
    Requirement already satisfied, skipping upgrade: requests-oauthlib>=0.7.0 in ./env/lib/python3.5/site-packages (from google-auth-oauthlib[tool]) (1.0.0)
    Requirement already satisfied, skipping upgrade: click; extra == "tool" in ./env/lib/python3.5/site-packages (from google-auth-oauthlib[tool]) (6.7)
    Requirement already satisfied, skipping upgrade: cachetools>=2.0.0 in ./env/lib/python3.5/site-packages (from google-auth->google-auth-oauthlib[tool]) (3.0.0)
    Requirement already satisfied, skipping upgrade: six>=1.9.0 in ./env/lib/python3.5/site-packages (from google-auth->google-auth-oauthlib[tool]) (1.12.0)
    Requirement already satisfied, skipping upgrade: rsa>=3.1.4 in ./env/lib/python3.5/site-packages (from google-auth->google-auth-oauthlib[tool]) (4.0)
    Requirement already satisfied, skipping upgrade: pyasn1-modules>=0.2.1 in ./env/lib/python3.5/site-packages (from google-auth->google-auth-oauthlib[tool]) (0.2.2)
    Requirement already satisfied, skipping upgrade: oauthlib>=0.6.2 in ./env/lib/python3.5/site-packages (from requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]) (2.1.0)
    Requirement already satisfied, skipping upgrade: requests>=2.0.0 in ./env/lib/python3.5/site-packages (from requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]) (2.21.0)
    Requirement already satisfied, skipping upgrade: pyasn1>=0.1.3 in ./env/lib/python3.5/site-packages (from rsa>=3.1.4->google-auth->google-auth-oauthlib[tool]) (0.4.4)
    Requirement already satisfied, skipping upgrade: chardet<3.1.0,>=3.0.2 in ./env/lib/python3.5/site-packages (from requests>=2.0.0->requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]) (3.0.4)
    Requirement already satisfied, skipping upgrade: idna<2.9,>=2.5 in ./env/lib/python3.5/site-packages (from requests>=2.0.0->requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]) (2.8)
    Requirement already satisfied, skipping upgrade: certifi>=2017.4.17 in ./env/lib/python3.5/site-packages (from requests>=2.0.0->requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]) (2018.11.29)
    Requirement already satisfied, skipping upgrade: urllib3<1.25,>=1.21.1 in ./env/lib/python3.5/site-packages (from requests>=2.0.0->requests-oauthlib>=0.7.0->google-auth-oauthlib[tool]) (1.24.1)
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=kEQPI0umtxZqMEqW1al51aZZHifHu6&access_type=offline&prompt=consent
    Enter the authorization code: google-oauthlib-tool --client-secrets path/to/credentials.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --hea     
    Traceback (most recent call last):
      File "/home/csk/env/bin/google-oauthlib-tool", line 11, in <module>
        sys.exit(main())
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 722, in __call__
        return self.main(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 697, in main
        rv = self.invoke(ctx)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 895, in invoke
        return ctx.invoke(self.callback, **ctx.params)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 535, in invoke
        return callback(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/tool/__main__.py", line 106, in main
        creds = flow.run_console()
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 364, in run_console
        self.fetch_token(code=code)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 241, in fetch_token
        self.client_config['token_uri'], **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/requests_oauthlib/oauth2_session.py", line 244, in fetch_token
        self._client.parse_request_body_response(r.text, scope=self.scope)
      File "/home/csk/env/lib/python3.5/site-packages/oauthlib/oauth2/rfc6749/clients/base.py", line 411, in parse_request_body_response
        self.token = parse_token_response(body, scope=scope)
      File "/home/csk/env/lib/python3.5/site-packages/oauthlib/oauth2/rfc6749/parameters.py", line 379, in parse_token_response
        validate_token_parameters(params)
      File "/home/csk/env/lib/python3.5/site-packages/oauthlib/oauth2/rfc6749/parameters.py", line 386, in validate_token_parameters
        raise_from_error(params.get('error'), params)
      File "/home/csk/env/lib/python3.5/site-packages/oauthlib/oauth2/rfc6749/errors.py", line 415, in raise_from_error
        raise cls(**kwargs)
    oauthlib.oauth2.rfc6749.errors.InvalidGrantError: (invalid_grant) Malformed auth code.
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=e0ns4HDZa3hvuYAqdTLCqMM23nn1nn&access_type=offline&prompt=consent
    Enter the authorization code: 
    Traceback (most recent call last):
      File "/home/csk/env/bin/google-oauthlib-tool", line 11, in <module>
        sys.exit(main())
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 722, in __call__
        return self.main(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 697, in main
        rv = self.invoke(ctx)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 895, in invoke
        return ctx.invoke(self.callback, **ctx.params)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 535, in invoke
        return callback(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/tool/__main__.py", line 106, in main
        creds = flow.run_console()
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 364, in run_console
        self.fetch_token(code=code)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 241, in fetch_token
        self.client_config['token_uri'], **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/requests_oauthlib/oauth2_session.py", line 192, in fetch_token
        raise ValueError('Please supply either code or '
    ValueError: Please supply either code or authorization_response parameters.
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=zTLwfqkf7XZMT06BF8dae8tOmO5nTN&prompt=consent&access_type=offline
    Enter the authorization code: 
    Traceback (most recent call last):
      File "/home/csk/env/bin/google-oauthlib-tool", line 11, in <module>
        sys.exit(main())
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 722, in __call__
        return self.main(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 697, in main
        rv = self.invoke(ctx)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 895, in invoke
        return ctx.invoke(self.callback, **ctx.params)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 535, in invoke
        return callback(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/tool/__main__.py", line 106, in main
        creds = flow.run_console()
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 364, in run_console
        self.fetch_token(code=code)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 241, in fetch_token
        self.client_config['token_uri'], **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/requests_oauthlib/oauth2_session.py", line 192, in fetch_token
        raise ValueError('Please supply either code or '
    ValueError: Please supply either code or authorization_response parameters.
    (env) csk@csk-ai-revolution:~$ 
    (env) csk@csk-ai-revolution:~$ 
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --scope https://www.googleapis.com/auth/assistant-sdk-prototype \
    >       --save --headless --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json 
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=TJ2jXo6QDVMx6IEvaULupD3ziXe8JG&access_type=offline&prompt=consent
    Enter the authorization code: 
    Traceback (most recent call last):
      File "/home/csk/env/bin/google-oauthlib-tool", line 11, in <module>
        sys.exit(main())
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 722, in __call__
        return self.main(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 697, in main
        rv = self.invoke(ctx)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 895, in invoke
        return ctx.invoke(self.callback, **ctx.params)
      File "/home/csk/env/lib/python3.5/site-packages/click/core.py", line 535, in invoke
        return callback(*args, **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/tool/__main__.py", line 106, in main
        creds = flow.run_console()
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 364, in run_console
        self.fetch_token(code=code)
      File "/home/csk/env/lib/python3.5/site-packages/google_auth_oauthlib/flow.py", line 241, in fetch_token
        self.client_config['token_uri'], **kwargs)
      File "/home/csk/env/lib/python3.5/site-packages/requests_oauthlib/oauth2_session.py", line 192, in fetch_token
        raise ValueError('Please supply either code or '
    ValueError: Please supply either code or authorization_response parameters.
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --scope https://www.googleapis.com/auth/assistant-sdk-prototype       --save --headless --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json 
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=qGC9rFRtZBxpok37HkBBCEi2FUj8kF&access_type=offline&prompt=consent
    Enter the authorization code: ^[[A^Z
    [2]+  Stopped                 google-oauthlib-tool --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=xyWyBoUt9A27qgpf0y4MTjDo2Gser7&prompt=consent&access_type=offline
    Enter the authorization code: ^Z
    [3]+  Stopped                 google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=ZbftWEHkM7JtnKUqhfzPVF9lIftCau&access_type=offline&prompt=consent
    Enter the authorization code: ^[[A^C
    Aborted!
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=kjOa1uThp9B2wENBTEUfK6963pT9Vf&prompt=consent&access_type=offline
    Enter the authorization code: ^C
    Aborted!
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_674471958889-3tu5mn01hemh05jal54u6bt1cg7m2hvh.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=674471958889-3tu5mn01hemh05jal54u6bt1cg7m2hvh.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=mXedA5a4Ug2a0uQWAkr5FpJWsjBk9v&prompt=consent&access_type=offline
    Enter the authorization code: ^C
    Aborted!
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_674471958889-3tu5mn01hemh05jal54u6bt1cg7m2hvh.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=674471958889-3tu5mn01hemh05jal54u6bt1cg7m2hvh.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=Qp60QY9Jx7J7HKzyDswvcLby6j6zwG&prompt=consent&access_type=offline
    Enter the authorization code: 4/twAE6tvtc6VCl2MwcHTw27x7mupDzPUqNqsSvRWLBh5YyZ2r-qJeboo
    credentials saved: /home/csk/.config/google-oauthlib-tool/credentials.json
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-pushtotalk --project-id assistant-16f2e --device-model-id ga
    INFO:root:Connecting to embeddedassistant.googleapis.com
    WARNING:root:Device config not found: [Errno 2] No such file or directory: '/home/csk/.config/googlesamples-assistant/device_config.json'
    INFO:root:Registering device
    ERROR:root:Failed to register device: {
      "error": {
        "code": 403,
        "message": "Google Assistant API has not been used in project 674471958889 before or it is disabled. Enable it by visiting https://console.developers.google.com/apis/api/embeddedassistant.googleapis.com/overview?project=674471958889 then retry. If you enabled this API recently, wait a few minutes for the action to propagate to our systems and retry.",
        "status": "PERMISSION_DENIED",
        "details": [
          {
            "@type": "type.googleapis.com/google.rpc.Help",
            "links": [
              {
                "description": "Google developers console API activation",
                "url": "https://console.developers.google.com/apis/api/embeddedassistant.googleapis.com/overview?project=674471958889"
              }
            ]
          }
        ]
      }
    }
    
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-pushtotalk --project-id assistant-16f2e --device-model-id assistant-16f2e-ga-v49sgp
    INFO:root:Connecting to embeddedassistant.googleapis.com
    WARNING:root:Device config not found: [Errno 2] No such file or directory: '/home/csk/.config/googlesamples-assistant/device_config.json'
    INFO:root:Registering device
    ERROR:root:Failed to register device: {
      "error": {
        "code": 403,
        "message": "Google Assistant API has not been used in project 674471958889 before or it is disabled. Enable it by visiting https://console.developers.google.com/apis/api/embeddedassistant.googleapis.com/overview?project=674471958889 then retry. If you enabled this API recently, wait a few minutes for the action to propagate to our systems and retry.",
        "status": "PERMISSION_DENIED",
        "details": [
          {
            "@type": "type.googleapis.com/google.rpc.Help",
            "links": [
              {
                "description": "Google developers console API activation",
                "url": "https://console.developers.google.com/apis/api/embeddedassistant.googleapis.com/overview?project=674471958889"
              }
            ]
          }
        ]
      }
    }
    
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=2xxldIbky6v1GwESNimdXPnJAMYVAp&prompt=consent&access_type=offline
    Enter the authorization code: ^[[B^[[B^[[A^Z
    [4]+  Stopped                 google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    (env) csk@csk-ai-revolution:~$ google-oauthlib-tool --client-secrets /home/csk/Downloads/client_secret_674471958889-3tu5mn01hemh05jal54u6bt1cg7m2hvh.apps.googleusercontent.com.json --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless
    Please visit this URL to authorize this application: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=674471958889-3tu5mn01hemh05jal54u6bt1cg7m2hvh.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fassistant-sdk-prototype&state=BGPL9eKfZzFoCwd6A7DNqlDtTvTibP&access_type=offline&prompt=consent
    Enter the authorization code: 4/twDuEPegrUNqTfNrDrxFCjCoj0vj6qBObzEDpka1KOI5XeuqHxh3s2I
    credentials saved: /home/csk/.config/google-oauthlib-tool/credentials.json
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-pushtotalk --project-id assistant-16f2e --device-model-id assistant-16f2e-ga-v49sgpINFO:root:Connecting to embeddedassistant.googleapis.com
    WARNING:root:Device config not found: [Errno 2] No such file or directory: '/home/csk/.config/googlesamples-assistant/device_config.json'
    INFO:root:Registering device
    ERROR:root:Failed to register device: {
      "error": {
        "code": 403,
        "message": "Google Assistant API has not been used in project 674471958889 before or it is disabled. Enable it by visiting https://console.developers.google.com/apis/api/embeddedassistant.googleapis.com/overview?project=674471958889 then retry. If you enabled this API recently, wait a few minutes for the action to propagate to our systems and retry.",
        "status": "PERMISSION_DENIED",
        "details": [
          {
            "@type": "type.googleapis.com/google.rpc.Help",
            "links": [
              {
                "description": "Google developers console API activation",
                "url": "https://console.developers.google.com/apis/api/embeddedassistant.googleapis.com/overview?project=674471958889"
              }
            ]
          }
        ]
      }
    }
    
    (env) csk@csk-ai-revolution:~$ ^C
    (env) csk@csk-ai-revolution:~$ python -m devicetool register --model 'assistant-16f2e-ga-v49sgp' --type LIGHT --trait action.devices.traits.OnOff
    /home/csk/env/bin/python: No module named devicetool
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool register-device assistant-16f2e-ga-v49sgp
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool register-device assistant-16f2e-ga-v49sgp --project-id assistant-16f2e
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool register-device  --project-id assistant-16f2e
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool --project-id assistant-16f2e
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing command.
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool register-device --device assistant-16f2e
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool register-device --project-id assistant-16f2e
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool register-device --model assistant-16f2e
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~$ ^C
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool register-device --project-id assistant-16f2e --device-model-id assistant-16f2e-ga-v49sgp
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool  --project-id assistant-16f2e --device-model-id assistant-16f2e-ga-v49sgp
    Error: no such option: --device-model-id
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool  --project-id assistant-16f2e --device assistant-16f2e-ga-v49sgp
    Error: no such option: --device
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool  --project-id assistant-16f2e --client-secrets /home/csk/Downloads/
    Algo_ver2.docx
    Anaconda3-5.2.0-Linux-x86_64.sh
    beginners_python_cheat_sheet_pcc_all.pdf
    client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json
    client_secret_674471958889-3tu5mn01hemh05jal54u6bt1cg7m2hvh.apps.googleusercontent.com.json
    cryptography_mp4.ipynb
    data/
    data.zip
    eclipse/
    eclipse-jee-2018-09-linux-gtk-x86_64.tar.gz
    Falls9.mov
    firefox-62.0.2.tar.bz2
    glove.6B.100d.txt.zip
    google-chrome-stable_current_amd64 (1).deb
    google-chrome-stable_current_amd64.deb
    image_cryptograpy-master.zip
    jdk1.8.0_181/
    jdk-8u181-linux-x64.rpm
    jdk-8u181-linux-x64.tar.gz
    LM-LSTM-CRF-master/
    LM-LSTM-CRF-master.zip
    .~lock.Algo_ver2.docx#
    My Project 36579-d6893ec94393.json
    mysql-8.0.12-linux-glibc2.12-x86_64.tar
    mysql-8.0.12-linux-glibc2.12-x86_64.tar (1).xz
    mysql-8.0.12-linux-glibc2.12-x86_64.tar.xz
    mysql-apt-config_0.8.10-1_all (1).deb
    mysql-apt-config_0.8.10-1_all.deb
    mysql-test-8.0.12-linux-glibc2.12-x86_64.tar.xz
    mysql-workbench-community_8.0.12-1ubuntu18.04_amd64.deb
    out.avi
    own_project_doc2vec.py
    pycharm-community-2018.2/
    pycharm-community-2018.2.tar.gz
    SampleVideo_1280x720_1mb (1).mp4
    skypeforlinux-64.deb
    skypeforlinux-64.rpm
    SoapUI-x64-5.4.0.sh
    sp87428.exe
    swift-4.1.3-RELEASE-ubuntu14.04/
    swift-4.1.3-RELEASE-ubuntu14.04 (1).tar.gz
    swift-4.1.3-RELEASE-ubuntu14.04.tar.gz
    transcripts.csv
    video.mp4
    videoplayback (1).mp4
    videoplayback (2).mp4
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool  --project-id assistant-16f2e --client-secrets /home/csk/Downloads/client_secret_
    client_secret_269317379742-iouv6tn1unbclr356b045g17ju4oe0qq.apps.googleusercontent.com.json
    client_secret_674471958889-3tu5mn01hemh05jal54u6bt1cg7m2hvh.apps.googleusercontent.com.json
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool  --project-id assistant-16f2e --client-secrets /home/csk/Downloads/client_secret_674471958889-3tu5mn01hemh05jal54u6bt1cg7m2hvh.apps.googleusercontent.com.json 
    Error: no such option: --client-secrets
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool --project-id assistant-16f2e --client-secrets /home/csk/Downloads/client_secret_674471958889-3tu5mn01hemh05jal54u6bt1cg7m2hvh.apps.googleusercontent.com.json 
    Error: no such option: --client-secrets
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool --help
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Options:
      --project-id TEXT    Enter the Google Developer Project ID that you want to
                           use with the registration tool. If you don't use this
                           flag, the tool will use the project listed in the
                           <client_secret_client-id.json> file you specify with
                           the --client-secrets flag.  [required]
      --verbose            Shows detailed JSON response
      --api-endpoint TEXT  Hostname for the Google Assistant API. Do not use this
                           flag unless explicitly instructed.  [default:
                           embeddedassistant.googleapis.com]
      --credentials TEXT   File location of the generated credentials file. The
                           google-oauthlib-tool generates this file after
                           authorizing the user with the <client_secret_client-
                           id.json> file. This credentials file authorizes access
                           to the Google Assistant API. You can use this flag if
                           the credentials were generated in a location that is
                           different than the default.  [default:
                           /home/csk/.config/google-oauthlib-
                           tool/credentials.json]
      --help               Show this message and exit.
    
    Commands:
      delete           Delete given device model or instance.
      get              Gets all of the information (fields) for a...
      list             Lists all of the device models and/or...
      register         Registers a device model and instance.
      register-device  Registers a device instance under an existing...
      register-model   Registers a device model.
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool --project-id assistant-16f2e --cre^C
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing command.
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool  --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing command.
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool  register-device --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool  register --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool  register-model --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool   --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.jsonUsage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing command.
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool   --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json register-device
    Usage: googlesamples-assistant-devicetool register-device [OPTIONS]
    
    Error: Missing option "--device".
    (env) csk@csk-ai-revolution:~$ googlesamples-assistant-devicetool   --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json python -m audio_helpers
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: No such command "python".
    (env) csk@csk-ai-revolution:~$ python -m audio_helpers
    /home/csk/env/bin/python: No module named audio_helpers
    (env) csk@csk-ai-revolution:~$ nano req.txt
    (env) csk@csk-ai-revolution:~$ pip install -r req.txt 
    Collecting google-assistant-grpc==0.2.1.dev1 (from -r req.txt (line 1))
      Downloading https://files.pythonhosted.org/packages/b2/5c/51226f560d54dd621bf7050114f7aa2a7757459acd46d0dc711578840f59/google_assistant_grpc-0.2.1.dev1-py2.py3-none-any.whl
    Requirement already satisfied: google-auth-oauthlib<0.3,>=0.1.0 in ./env/lib/python3.5/site-packages (from -r req.txt (line 2)) (0.2.0)
    Requirement already satisfied: urllib3[secure]<2,>=1.21 in ./env/lib/python3.5/site-packages (from -r req.txt (line 3)) (1.24.1)
    Requirement already satisfied: sounddevice<0.4,>=0.3.7 in ./env/lib/python3.5/site-packages (from -r req.txt (line 4)) (0.3.12)
    Requirement already satisfied: click<7,>=6.7 in ./env/lib/python3.5/site-packages (from -r req.txt (line 5)) (6.7)
    Requirement already satisfied: tenacity<5,>=4.1.0 in ./env/lib/python3.5/site-packages (from -r req.txt (line 6)) (4.12.0)
    Requirement already satisfied: futures<4,>=3.1.1 in ./env/lib/python3.5/site-packages (from -r req.txt (line 7)) (3.1.1)
    Requirement already satisfied: pathlib2<3,>=2.3.0 in ./env/lib/python3.5/site-packages (from -r req.txt (line 8)) (2.3.3)
    Requirement already satisfied: googleapis-common-protos>=1.5.2 in ./env/lib/python3.5/site-packages (from google-assistant-grpc==0.2.1.dev1->-r req.txt (line 1)) (1.5.5)
    Requirement already satisfied: grpcio>=1.3.5 in ./env/lib/python3.5/site-packages (from google-assistant-grpc==0.2.1.dev1->-r req.txt (line 1)) (1.17.1)
    Requirement already satisfied: requests-oauthlib>=0.7.0 in ./env/lib/python3.5/site-packages (from google-auth-oauthlib<0.3,>=0.1.0->-r req.txt (line 2)) (1.0.0)
    Requirement already satisfied: google-auth in ./env/lib/python3.5/site-packages (from google-auth-oauthlib<0.3,>=0.1.0->-r req.txt (line 2)) (1.6.2)
    Requirement already satisfied: cryptography>=1.3.4; extra == "secure" in ./env/lib/python3.5/site-packages (from urllib3[secure]<2,>=1.21->-r req.txt (line 3)) (2.4.2)
    Requirement already satisfied: certifi; extra == "secure" in ./env/lib/python3.5/site-packages (from urllib3[secure]<2,>=1.21->-r req.txt (line 3)) (2018.11.29)
    Requirement already satisfied: pyOpenSSL>=0.14; extra == "secure" in ./env/lib/python3.5/site-packages (from urllib3[secure]<2,>=1.21->-r req.txt (line 3)) (18.0.0)
    Requirement already satisfied: ipaddress; extra == "secure" in ./env/lib/python3.5/site-packages (from urllib3[secure]<2,>=1.21->-r req.txt (line 3)) (1.0.22)
    Requirement already satisfied: idna>=2.0.0; extra == "secure" in ./env/lib/python3.5/site-packages (from urllib3[secure]<2,>=1.21->-r req.txt (line 3)) (2.8)
    Requirement already satisfied: CFFI>=1.0 in ./env/lib/python3.5/site-packages (from sounddevice<0.4,>=0.3.7->-r req.txt (line 4)) (1.11.5)
    Requirement already satisfied: six>=1.9.0 in ./env/lib/python3.5/site-packages (from tenacity<5,>=4.1.0->-r req.txt (line 6)) (1.12.0)
    Requirement already satisfied: protobuf>=3.0.0 in ./env/lib/python3.5/site-packages (from googleapis-common-protos>=1.5.2->google-assistant-grpc==0.2.1.dev1->-r req.txt (line 1)) (3.6.1)
    Requirement already satisfied: requests>=2.0.0 in ./env/lib/python3.5/site-packages (from requests-oauthlib>=0.7.0->google-auth-oauthlib<0.3,>=0.1.0->-r req.txt (line 2)) (2.21.0)
    Requirement already satisfied: oauthlib>=0.6.2 in ./env/lib/python3.5/site-packages (from requests-oauthlib>=0.7.0->google-auth-oauthlib<0.3,>=0.1.0->-r req.txt (line 2)) (2.1.0)
    Requirement already satisfied: cachetools>=2.0.0 in ./env/lib/python3.5/site-packages (from google-auth->google-auth-oauthlib<0.3,>=0.1.0->-r req.txt (line 2)) (3.0.0)
    Requirement already satisfied: pyasn1-modules>=0.2.1 in ./env/lib/python3.5/site-packages (from google-auth->google-auth-oauthlib<0.3,>=0.1.0->-r req.txt (line 2)) (0.2.2)
    Requirement already satisfied: rsa>=3.1.4 in ./env/lib/python3.5/site-packages (from google-auth->google-auth-oauthlib<0.3,>=0.1.0->-r req.txt (line 2)) (4.0)
    Requirement already satisfied: asn1crypto>=0.21.0 in ./env/lib/python3.5/site-packages (from cryptography>=1.3.4; extra == "secure"->urllib3[secure]<2,>=1.21->-r req.txt (line 3)) (0.24.0)
    Requirement already satisfied: pycparser in ./env/lib/python3.5/site-packages (from CFFI>=1.0->sounddevice<0.4,>=0.3.7->-r req.txt (line 4)) (2.19)
    Requirement already satisfied: setuptools in ./env/lib/python3.5/site-packages (from protobuf>=3.0.0->googleapis-common-protos>=1.5.2->google-assistant-grpc==0.2.1.dev1->-r req.txt (line 1)) (40.6.3)
    Requirement already satisfied: chardet<3.1.0,>=3.0.2 in ./env/lib/python3.5/site-packages (from requests>=2.0.0->requests-oauthlib>=0.7.0->google-auth-oauthlib<0.3,>=0.1.0->-r req.txt (line 2)) (3.0.4)
    Requirement already satisfied: pyasn1<0.5.0,>=0.4.1 in ./env/lib/python3.5/site-packages (from pyasn1-modules>=0.2.1->google-auth->google-auth-oauthlib<0.3,>=0.1.0->-r req.txt (line 2)) (0.4.4)
    Installing collected packages: google-assistant-grpc
      Found existing installation: google-assistant-grpc 0.2.0
        Uninstalling google-assistant-grpc-0.2.0:
          Successfully uninstalled google-assistant-grpc-0.2.0
    Successfully installed google-assistant-grpc-0.2.1.dev1
    (env) csk@csk-ai-revolution:~$ python -m audio_helpers
    /home/csk/env/bin/python: No module named audio_helpers
    (env) csk@csk-ai-revolution:~$ sudo apt-get install portaudio19-dev libffi-dev libssl-dev
    [sudo] password for csk: 
    Reading package lists... Done
    Building dependency tree       
    Reading state information... Done
    libffi-dev is already the newest version (3.2.1-4).
    portaudio19-dev is already the newest version (19+svn20140130-1build1).
    libssl-dev is already the newest version (1.0.2g-1ubuntu4.14).
    0 upgraded, 0 newly installed, 0 to remove and 560 not upgraded.
    (env) csk@csk-ai-revolution:~$ python -m audio_helpers
    /home/csk/env/bin/python: No module named audio_helpers
    (env) csk@csk-ai-revolution:~$ pushtotalk.py
    pushtotalk.py: command not found
    (env) csk@csk-ai-revolution:~$ nano pushtotalk.py
    (env) csk@csk-ai-revolution:~$ nano pushtotalk.py
    (env) csk@csk-ai-revolution:~$ python -m pushtotalk  --project-id assistant-16f2e --device-model-id assistant-16f2e-ga-v49sgpTraceback (most recent call last):
      File "/home/csk/pushtotalk.py", line 40, in <module>
        from . import (
    SystemError: Parent module '' not loaded, cannot perform relative import
    
    During handling of the above exception, another exception occurred:
    
    Traceback (most recent call last):
      File "/usr/lib/python3.5/runpy.py", line 184, in _run_module_as_main
        "__main__", mod_spec)
      File "/usr/lib/python3.5/runpy.py", line 85, in _run_code
        exec(code, run_globals)
      File "/home/csk/pushtotalk.py", line 47, in <module>
        import assistant_helpers
    ImportError: No module named 'assistant_helpers'
    (env) csk@csk-ai-revolution:~$ nano assistant_helpers.py
    (env) csk@csk-ai-revolution:~$ python -m pushtotalk  --project-id assistant-16f2e --device-model-id assistant-16f2e-ga-v49sgp
    Traceback (most recent call last):
      File "/home/csk/pushtotalk.py", line 40, in <module>
        from . import (
    SystemError: Parent module '' not loaded, cannot perform relative import
    
    During handling of the above exception, another exception occurred:
    
    Traceback (most recent call last):
      File "/usr/lib/python3.5/runpy.py", line 184, in _run_module_as_main
        "__main__", mod_spec)
      File "/usr/lib/python3.5/runpy.py", line 85, in _run_code
        exec(code, run_globals)
      File "/home/csk/pushtotalk.py", line 48, in <module>
        import audio_helpers
    ImportError: No module named 'audio_helpers'
    (env) csk@csk-ai-revolution:~$ nano audio_helpers.py
    (env) csk@csk-ai-revolution:~$ git clone https://github.com/googlesamples/assistant-sdk-python/tree/master/google-assistant-sdk/googlesamples/assistant/grpc
    Cloning into 'grpc'...
    fatal: repository 'https://github.com/googlesamples/assistant-sdk-python/tree/master/google-assistant-sdk/googlesamples/assistant/grpc/' not found
    (env) csk@csk-ai-revolution:~$ git clone https://github.com/googlesamples/assistant-sdk-python
    Cloning into 'assistant-sdk-python'...
    remote: Enumerating objects: 2009, done.
    remote: Total 2009 (delta 0), reused 0 (delta 0), pack-reused 2009
    Receiving objects: 100% (2009/2009), 665.26 KiB | 71.00 KiB/s, done.
    Resolving deltas: 100% (1120/1120), done.
    Checking connectivity... done.
    (env) csk@csk-ai-revolution:~$ ls
    31131036_1657332284322369_6524597261597409280_o.jpg  DSC_2908.JPG                    java_error_in_PYCHARM_2447.log  pushtotalk.py                 SmartBear
    anaconda                                             eclipse-workspace               java_error_in_PYCHARM_3366.log  __pycache__                   SoapUI-Tutorials
    assistant_helpers.py                                 env                             java_error_in_PYCHARM_3671.log  PycharmProjects               table_detection_dl
    assistant-sdk-python                                 examples.desktop                java_error_in_PYCHARM_3732.log  Python_Instrction_manual.odt  Templates
    audio_helpers.py                                     java_error_in_PYCHARM_2068.log  java_error_in_PYCHARM.hprof     req.txt                       Videos
    Desktop                                              java_error_in_PYCHARM_2348.log  Music                           sample.mwb
    Documents                                            java_error_in_PYCHARM_2362.log  Pictures                        sample.mwb.bak
    Downloads                                            java_error_in_PYCHARM_2420.log  Public                          Sathish
    (env) csk@csk-ai-revolution:~$ cd a
    anaconda/             assistant-sdk-python/ 
    (env) csk@csk-ai-revolution:~$ cd assistant-sdk-python/
    .git/                     google-assistant-grpc/    google-assistant-library/ google-assistant-sdk/     
    (env) csk@csk-ai-revolution:~$ cd assistant-sdk-python/google-assistant-grpc/google/assistant/embedded/v1alpha
    v1alpha1/ v1alpha2/ 
    (env) csk@csk-ai-revolution:~$ cd assistant-sdk-python/google-assistant-sdk/
    googlesamples/ tests/         
    (env) csk@csk-ai-revolution:~$ cd assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/
    grpc/    library/ 
    (env) csk@csk-ai-revolution:~$ cd assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc/
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ python -m pushtotalk  --project-id assistant-16f2e --device-model-id assistant-16f2e-ga-v49sgp
    INFO:root:Connecting to embeddedassistant.googleapis.com
    WARNING:root:Device config not found: [Errno 2] No such file or directory: '/home/csk/.config/googlesamples-assistant/device_config.json'
    INFO:root:Registering device
    ERROR:root:Failed to register device: {
      "error": {
        "code": 403,
        "message": "Google Assistant API has not been used in project 674471958889 before or it is disabled. Enable it by visiting https://console.developers.google.com/apis/api/embeddedassistant.googleapis.com/overview?project=674471958889 then retry. If you enabled this API recently, wait a few minutes for the action to propagate to our systems and retry.",
        "status": "PERMISSION_DENIED",
        "details": [
          {
            "@type": "type.googleapis.com/google.rpc.Help",
            "links": [
              {
                "description": "Google developers console API activation",
                "url": "https://console.developers.google.com/apis/api/embeddedassistant.googleapis.com/overview?project=674471958889"
              }
            ]
          }
        ]
      }
    }
    
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool register --model assistant-16f2eUsage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool register --project-id assistant-16f2e
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool register --help
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Error: Missing option "--project-id".
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --help
    Usage: googlesamples-assistant-devicetool [OPTIONS] COMMAND [ARGS]...
    
    Options:
      --project-id TEXT    Enter the Google Developer Project ID that you want to
                           use with the registration tool. If you don't use this
                           flag, the tool will use the project listed in the
                           <client_secret_client-id.json> file you specify with
                           the --client-secrets flag.  [required]
      --verbose            Shows detailed JSON response
      --api-endpoint TEXT  Hostname for the Google Assistant API. Do not use this
                           flag unless explicitly instructed.  [default:
                           embeddedassistant.googleapis.com]
      --credentials TEXT   File location of the generated credentials file. The
                           google-oauthlib-tool generates this file after
                           authorizing the user with the <client_secret_client-
                           id.json> file. This credentials file authorizes access
                           to the Google Assistant API. You can use this flag if
                           the credentials were generated in a location that is
                           different than the default.  [default:
                           /home/csk/.config/google-oauthlib-
                           tool/credentials.json]
      --help               Show this message and exit.
    
    Commands:
      delete           Delete given device model or instance.
      get              Gets all of the information (fields) for a...
      list             Lists all of the device models and/or...
      register         Registers a device model and instance.
      register-device  Registers a device instance under an existing...
      register-model   Registers a device model.
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/Downloads/client_secret_674471958889-3tu5mn01hemh05jal54u6bt1cg7m2hvh.apps.googleusercontent.com.json register --model 
    Error: Error loading credentials: __init__() got an unexpected keyword argument 'installed'.
    Run google-oauthlib-tool to initialize new OAuth 2.0 credentials.
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.c register --model 
    .cache/  .conda/  .config/ 
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/ register --model 
    autostart/             eog/                   google-chrome/         libaccounts-glib/      monitors.xml           ubuntu-amazon-default/ user-dirs.dirs
    chromium/              evolution/             google-oauthlib-tool/  libreoffice/           nautilus/              ubuntu-ui-toolkit/     user-dirs.locale
    compiz-1/              gedit/                 gtk-2.0/               matplotlib/            pulse/                 unity/                 
    dconf/                 gnome-control-center/  gtk-3.0/               menus/                 skypeforlinux/         update-notifier/       
    dell-recovery/         gnome-session/         ibus/                  mimeapps.list          totem/                 upstart/               
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/g register --model 
    gedit/                gnome-control-center/ gnome-session/        google-chrome/        google-oauthlib-tool/ gtk-2.0/              gtk-3.0/
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json register --model 
    Error: --model option requires an argument
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json register --model assistant-16f2e-ga-v49sgp --type LIGHT  
    Usage: googlesamples-assistant-devicetool register [OPTIONS]
    
    Error: Missing option "--manufacturer".
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json register --model assistant-16f2e-ga-v49sgp --type LIGHT  --manufacturer ga
    Usage: googlesamples-assistant-devicetool register [OPTIONS]
    
    Error: Missing option "--product-name".
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json register --model assistant-16f2e-ga-v49sgp --type LIGHT  --manufacturer ga --product-name ga
    Usage: googlesamples-assistant-devicetool register [OPTIONS]
    
    Error: Missing option "--device".
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json register --model assistant-16f2e-ga-v49sgp --type LIGHT  --manufacturer ga --product-name ga --device 
    Error: --device option requires an argument
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ nano /home/csk/.config/google-oauthlib-
    Use "fg" to return to nano.
    
    [5]+  Stopped                 nano /home/csk/.config/google-oauthlib-
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ nano /home/csk/.config/google-oauthlib-tool/credentials.json 
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json register --model assistant-16f2e-ga-v49sgp --type LIGHT  --manufacturer ga --product-name ga --device hhhh
    Usage: googlesamples-assistant-devicetool register [OPTIONS]
    
    Error: Missing option "--client-type".  Choose from SERVICE, LIBRARY.
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json register --model assistant-16f2e-ga-v49sgp --type LIGHT  --manufacturer ga --product-name ga --device hhhh --client-type SERVICE
    Creating new device model
    Error: Failed to register model: 403
    Google Assistant API has not been used in project 674471958889 before or it is disabled. Enable it by visiting https://console.developers.google.com/apis/api/embeddedassistant.googleapis.com/overview?project=674471958889 then retry. If you enabled this API recently, wait a few minutes for the action to propagate to our systems and retry.
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json register --model assistant-16f2e-ga-v49sgp --type LIGHT  --manufacturer ga --product-name ga --device hhhh --client-type SERVICE
    \Creating new device model
    Error: Failed to register model: 403
    Google Assistant API has not been used in project 674471958889 before or it is disabled. Enable it by visiting https://console.developers.google.com/apis/api/embeddedassistant.googleapis.com/overview?project=674471958889 then retry. If you enabled this API recently, wait a few minutes for the action to propagate to our systems and retry.
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json register-device --model assistant-16f2e-ga-v49sgp --type LIGHT  --manufacturer ga --product-name ga --device hhhh --client-type SERVICE
    Error: no such option: --type
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ googlesamples-assistant-devicetool --project-id assistant-16f2e --credentials /home/csk/.config/google-oauthlib-tool/credentials.json register --model assistant-16f2e-ga-v49sgp --type LIGHT  --manufacturer ga --product-name ga --device assistant-16f2e-ga-v49sgp --client-type SERVICE
    Creating new device model
    Error: Failed to register model: 403
    Google Assistant API has not been used in project 674471958889 before or it is disabled. Enable it by visiting https://console.developers.google.com/apis/api/embeddedassistant.googleapis.com/overview?project=674471958889 then retry. If you enabled this API recently, wait a few minutes for the action to propagate to our systems and retry.
    (env) csk@csk-ai-revolution:~/assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/grpc$ 
