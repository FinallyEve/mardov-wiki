debconf: unable to initialize frontend: Dialog
debconf: (Dialog frontend will not work on a dumb terminal, an emacs shell buffer, or without a controlling terminal.)
debconf: falling back to frontend: Readline
debconf: unable to initialize frontend: Readline
debconf: (This frontend requires a controlling tty.)
debconf: falling back to frontend: Teletype
dpkg-preconfigure: unable to re-open stdin: 
Selecting previously unselected package poppler-data.
(Reading database ... (Reading database ... 5%(Reading database ... 10%(Reading database ... 15%(Reading database ... 20%(Reading database ... 25%(Reading database ... 30%(Reading database ... 35%(Reading database ... 40%(Reading database ... 45%(Reading database ... 50%(Reading database ... 55%(Reading database ... 60%(Reading database ... 65%(Reading database ... 70%(Reading database ... 75%(Reading database ... 80%(Reading database ... 85%(Reading database ... 90%(Reading database ... 95%(Reading database ... 100%(Reading database ... 112120 files and directories currently installed.)
Preparing to unpack .../0-poppler-data_0.4.11-1_all.deb ...
Unpacking poppler-data (0.4.11-1) ...
Selecting previously unselected package libcmark-gfm0.29.0.gfm.3:amd64.
Preparing to unpack .../1-libcmark-gfm0.29.0.gfm.3_0.29.0.gfm.3-3_amd64.deb ...
Unpacking libcmark-gfm0.29.0.gfm.3:amd64 (0.29.0.gfm.3-3) ...
Selecting previously unselected package libcmark-gfm-extensions0.29.0.gfm.3:amd64.
Preparing to unpack .../2-libcmark-gfm-extensions0.29.0.gfm.3_0.29.0.gfm.3-3_amd64.deb ...
Unpacking libcmark-gfm-extensions0.29.0.gfm.3:amd64 (0.29.0.gfm.3-3) ...
Selecting previously unselected package liblcms2-2:amd64.
Preparing to unpack .../3-liblcms2-2_2.12~rc1-2build2_amd64.deb ...
Unpacking liblcms2-2:amd64 (2.12~rc1-2build2) ...
Selecting previously unselected package libpoppler118:amd64.
Preparing to unpack .../4-libpoppler118_22.02.0-2ubuntu0.12_amd64.deb ...
Unpacking libpoppler118:amd64 (22.02.0-2ubuntu0.12) ...
Selecting previously unselected package pandoc-data.
Preparing to unpack .../5-pandoc-data_2.9.2.1-3ubuntu2_all.deb ...
Unpacking pandoc-data (2.9.2.1-3ubuntu2) ...
Selecting previously unselected package pandoc.
Preparing to unpack .../6-pandoc_2.9.2.1-3ubuntu2_amd64.deb ...
Unpacking pandoc (2.9.2.1-3ubuntu2) ...
Selecting previously unselected package poppler-utils.
Preparing to unpack .../7-poppler-utils_22.02.0-2ubuntu0.12_amd64.deb ...
Unpacking poppler-utils (22.02.0-2ubuntu0.12) ...
Setting up liblcms2-2:amd64 (2.12~rc1-2build2) ...
Setting up poppler-data (0.4.11-1) ...
Setting up libpoppler118:amd64 (22.02.0-2ubuntu0.12) ...
Setting up libcmark-gfm0.29.0.gfm.3:amd64 (0.29.0.gfm.3-3) ...
Setting up libcmark-gfm-extensions0.29.0.gfm.3:amd64 (0.29.0.gfm.3-3) ...
Setting up poppler-utils (22.02.0-2ubuntu0.12) ...
Setting up pandoc-data (2.9.2.1-3ubuntu2) ...
Setting up pandoc (2.9.2.1-3ubuntu2) ...
Processing triggers for libc-bin (2.35-0ubuntu3.13) ...
Processing triggers for man-db (2.10.2-1) ...
Processing triggers for fontconfig (2.13.1-4.2ubuntu5) ...

Pending kernel upgrade!

Running kernel version:
  5.15.0-171-generic

Diagnostics:
  The currently running kernel version is not the expected kernel version 5.15.0-173-generic.

Restarting the system to load the new kernel will not be handled automatically, so you should consider rebooting. [Return]

Services to be restarted:
 systemctl restart packagekit.service
 systemctl restart polkit.service
 systemctl restart rsyslog.service
 systemctl restart systemd-journald.service
 /etc/needrestart/restart.d/systemd-manager
 systemctl restart systemd-networkd.service
 systemctl restart systemd-resolved.service
 systemctl restart systemd-timesyncd.service
 systemctl restart systemd-udevd.service

Service restarts being deferred:
 systemctl restart getty@tty1.service
 systemctl restart networkd-dispatcher.service
 systemctl restart systemd-logind.service
 systemctl restart unattended-upgrades.service
 systemctl restart user@1000.service

No containers need to be restarted.

No user sessions are running outdated binaries.

No VM guests are running outdated hypervisor (qemu) binaries on this host.
Defaulting to user installation because normal site-packages is not writeable
Requirement already satisfied: python-docx in ./.local/lib/python3.10/site-packages (1.2.0)
Collecting python-pptx
  Downloading python_pptx-1.0.2-py3-none-any.whl (472 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 472.8/472.8 KB 7.7 MB/s eta 0:00:00
Requirement already satisfied: lxml>=3.1.0 in ./.local/lib/python3.10/site-packages (from python-docx) (6.0.2)
Requirement already satisfied: typing_extensions>=4.9.0 in ./.local/lib/python3.10/site-packages (from python-docx) (4.15.0)
Collecting Pillow>=3.3.2
  Downloading pillow-12.1.1-cp310-cp310-manylinux_2_27_x86_64.manylinux_2_28_x86_64.whl (7.0 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 7.0/7.0 MB 23.7 MB/s eta 0:00:00
Collecting XlsxWriter>=0.5.7
  Downloading xlsxwriter-3.2.9-py3-none-any.whl (175 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 175.3/175.3 KB 33.2 MB/s eta 0:00:00
Installing collected packages: XlsxWriter, Pillow, python-pptx
Successfully installed Pillow-12.1.1 XlsxWriter-3.2.9 python-pptx-1.0.2
