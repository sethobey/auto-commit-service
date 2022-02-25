# auto-commit-service
Simple configurable auto-commit service for MacOS

## Install
1. Download or clone this repository
2. Run the `installer` script included in this repository
3. When prompted, input the system path of the directory you would like to auto-commit

To verify successful installation, you can run the command:
```shell
launchctl list | grep auto-commit
```

If successful, you should see the following output:
```shell
-	0	com.github.<username>.auto-commit
```

## Uninstall
1. Run the `uninstaller` script included in this repository
