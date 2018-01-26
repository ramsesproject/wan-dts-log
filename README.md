GridFTP logs we used in the paper "Cross-geography Scientific Data Transfer Trends and User Behavior Patterns"

Data fields

| Name            | Unit   | Description                                 |
|-----------------|--------|---------------------------------------------|
| appname         | N/A    | GridFTP client application name             |
| block_size      | byte   | disk blocksize used for transfer            |
| buffer_size     | byte   | tcp buffer size used for transfer           |
| end_time        | second | end time of transfer                        |
| ftp_return_code | N/A    | ftp result code (226 = success, 5xx = fail) |
| gftp_version    | N/A    | version string of GridFTP server            |
| server_id       | N/A    | A unique ID based on server IP address      |
| num_bytes       | byte   | number of bytes transferred                 |
| num_streams     | N/A    | number of parallel streams used             |
| num_stripes     | N/A    | number of stripes used                      |
| start_time      | second | start time of transfer                      |
| trans_type      | N/A    | transfer command: RETR, STOR, LIST, etc     |

All logs in 2017 are expected to be online around mid-February, 2018. Contact me if you cannot wait. Since the dataset is big, we are working to make it available online via other sharing service, e.g., [Data Sharing With Globus](https://www.globus.org/data-sharing). 