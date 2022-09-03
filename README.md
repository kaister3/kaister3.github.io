# kaister3.github.io

## windows terminal settings
    first uploaded in 09/02/2022

## move wsl away from system drive
    - check installation
      ```
      wsl --list -v
      ```
    - termniate target wsl
      ```
      wsl -t [Ubuntu]
      ```
    - export to a folder
      ```
      wsl --export [Ubuntu] "[dest location\exported.tar]"
    - unregister previous wsl
      ```
      wsl --unregister [Ubuntu]
      ```
    - import wsl to another folder
      ```
      wsl --import [Ubuntu] "[vhd location]" "[dest location\exported.tar]"
      ```

    - if you still want to use win terminal for wsl, add a profile in the setting tab of win terminal
