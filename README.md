shavar-list-creation
====================
```
usage: lists2safebrowsing.py [-h] [--disconnect_url DISCONNECT_URL]
                             [--allowlist_url ALLOWLIST_URL]
                             [--output_file OUTPUT_FILE] [--s3_url S3_URL]
                             [--s3_upload | --no_s3_upload]

Generate digest256 list from disconnect

optional arguments:
  -h, --help            show this help message and exit
  --disconnect_url DISCONNECT_URL
                        The location of the Disconnect list (default:
                        http://services.disconnect.me/disconnect-
                        plaintext.json)
  --allowlist_url ALLOWLIST_URL
                        The location of the allowlist (default:
                        https://raw.githubusercontent.com/mozilla-services
                        /shavar-list-exceptions/master/allow_list)
  --output_file OUTPUT_FILE
                        The location of the output digest256 list (default:
                        mozpub-track-digest256)
  --s3_url S3_URL       The bucket url to which to upload the output digest256
                        list, e.g. s3://mmc-shavar (default: )
  --s3_upload           Upload to S3 (default: False)
  --no_s3_upload        Don't upload to S3 (default: False)
```
