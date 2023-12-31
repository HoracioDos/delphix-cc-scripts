# Delphix CC Filesystem Mounts

```sh
# dpxcc_create_fsmounts.sh
# Created: Horacio Dos - 11/2023
# Parameters:
#
#   dpxcc_create_fsmounts.sh --help
#
#    Parameter             Short Description                                                        Default
#    --------------------- ----- ------------------------------------------------------------------ --------------
#    --fsmounts-file       -f    File containing FS Mounts                                          fsmounts.csv
#    --log-file            -o    Log file name                                                      Current date_time.log"
#    --proxy-bypass        -x    Proxy ByPass                                                       true
#    --https-insecure      -k    Make Https Insecure                                                false
#    --masking-engine      -m    Masking Engine Address                                             Required value
#    --masking-username    -u    Masking Engine User Name                                           Required value
#    --masking-pwd         -p    Masking Engine Password                                            Required value
#    --help                -h    Show this help
#     
#    Example: dpxcc_create_fsmounts.sh -m <MASKING IP> -u <MASKING User> -p <MASKING Password>
#
# dpxcc_get_fsmounts.sh --help
# Created: Horacio Dos - 11/2023
# Parameters:
#
#   dpxcc_get_fsmounts.sh --help
#
#    Parameter             Short Description                                                        Default
#    --------------------- ----- ------------------------------------------------------------------ --------------
#    --fsmounts-file       -f    FS Mounts Output File                                              connect_fsmounts.csv
#    --log-file            -o    Log file name                                                      Current date_time.log"
#    --proxy-bypass        -x    Proxy ByPass                                                       true
#    --https-insecure      -k    Make Https Insecure                                                false
#    --masking-engine      -m    Masking Engine Address                                             Required value
#    --masking-username    -u    Masking Engine User Name                                           Required value
#    --masking-pwd         -p    Masking Engine Password                                            Required value
#    --help                -h    Show this help
#     
#    Example: dpxcc_get_fsmounts.sh -m <MASKING IP> -u <MASKING User> -p <MASKING Password>
#
# dpxcc_connect_fsmounts.sh --help
# Created: Horacio Dos - 11/2023
# Parameters:
#
#   dpxcc_connect_fsmounts.sh --help
#
#    Parameter             Short Description                                                        Default
#    --------------------- ----- ------------------------------------------------------------------ --------------
#    --fsmounts-file       -f    FS Mounts Input File                                               connect_fsmounts.csv
#    --log-file            -o    Log file name                                                      Current date_time.log"
#    --proxy-bypass        -x    Proxy ByPass                                                       true
#    --https-insecure      -k    Make Https Insecure                                                false
#    --masking-engine      -m    Masking Engine Address                                             Required value
#    --masking-username    -u    Masking Engine User Name                                           Required value
#    --masking-pwd         -p    Masking Engine Password                                            Required value
#    --help                -h    Show this help
#     
#    Example: dpxcc_connect_fsmounts.sh -m <MASKING IP> -u <MASKING User> -p <MASKING Password>
#
# dpxcc_delete_fsmounts.sh --help
# Created: Horacio Dos - 11/2023
# Parameters:
#
#   dpxcc_delete_fsmounts.sh --help
#
#    Parameter             Short Description                                                        Default
#    --------------------- ----- ------------------------------------------------------------------ --------------
#    --fsmounts-file       -f    FS Mounts Input File                                               connect_fsmounts.csv
#    --log-file            -o    Log file name                                                      Current date_time.log"
#    --proxy-bypass        -x    Proxy ByPass                                                       true
#    --https-insecure      -k    Make Https Insecure                                                false
#    --masking-engine      -m    Masking Engine Address                                             Required value
#    --masking-username    -u    Masking Engine User Name                                           Required value
#    --masking-pwd         -p    Masking Engine Password                                            Required value
#    --help                -h    Show this help
#     
#    Example: dpxcc_delete_fsmounts.sh -m <MASKING IP> -u <MASKING User> -p <MASKING Password>
#
# dpxcc_disconnect_fsmounts.sh --help
# Created: Horacio Dos - 11/2023
# Parameters:
#
#   dpxcc_disconnect_fsmounts.sh --help
#
#    Parameter             Short Description                                                        Default
#    --------------------- ----- ------------------------------------------------------------------ --------------
#    --fsmounts-file       -f    FS Mounts Input File                                               connect_fsmounts.csv
#    --log-file            -o    Log file name                                                      Current date_time.log"
#    --proxy-bypass        -x    Proxy ByPass                                                       true
#    --https-insecure      -k    Make Https Insecure                                                false
#    --masking-engine      -m    Masking Engine Address                                             Required value
#    --masking-username    -u    Masking Engine User Name                                           Required value
#    --masking-pwd         -p    Masking Engine Password                                            Required value
#    --help                -h    Show this help
#     
#    Example: dpxcc_disconnect_fsmounts.sh -m <MASKING IP> -u <MASKING User> -p <MASKING Password>
#
```
