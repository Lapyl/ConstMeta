# ConstMeta
Constellation Network - Metagraph



TASK [Install requests module] ****************************************************************************************************************************************
fatal: [localhost]: FAILED! => {"changed": false, "cmd": ["/usr/bin/python3", "-m", "pip.__main__", "install", "requests"], "msg": "\n:stderr: error: externally-managed-environment\n\n× This environment is externally managed\n╰─> To install Python packages system-wide, try apt install\n    python3-xyz, where xyz is the package you are trying to\n    install.\n    \n    If you wish to install a non-Debian-packaged Python package,\n    create a virtual environment using python3 -m venv path/to/venv.\n    Then use path/to/venv/bin/python and path/to/venv/bin/pip. Make\n    sure you have python3-full installed.\n    \n    If you wish to install a non-Debian packaged Python application,\n    it may be easiest to use pipx install xyz, which will manage a\n    virtual environment for you. Make sure you have pipx installed.\n    \n    See /usr/share/doc/python3.12/README.venv for more information.\n\nnote: If you believe this is a mistake, please contact your Python installation or OS distribution provider. You can override this, at the risk of breaking your Python installation or OS, by passing --break-system-packages.\nhint: See PEP 668 for the detailed specification.\n"}

PLAY RECAP ************************************************************************************************************************************************************
localhost                  : ok=2    changed=0    unreachable=0    failed=1    skipped=2    rescued=0    ignored=0

Failing when starting nodes containers, take a look at the logs.
