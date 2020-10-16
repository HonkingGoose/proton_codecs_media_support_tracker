## WMVCore games

This table lists games which use the **WMVCore** framework.
It's called `wmvcore` in the Proton log files.

| Upstream Proton issue | Codecs used | Remarks |
| ---: | :---: | --- |
| #294 | WMV, VC-1 + WMA | From log: ```fixme:wmvcore:WMReader_Open``` |
| #296 | VC-1 / OGG | From log: ```fixme:wmvcore:WMCreateSyncReader ((nil), 1, 0x59299798): stub``` |
| #366 | VC-1 / WMA | From log: ```fixme:wmvcore:WMReader_Open``` |
| #576 | WMV3 and WVC1 for RE 0 HD Remaster| From log: ```fixme:wmvcore:WMCreateSyncReader ((nil), 1, 0x8411e08): stub``` |
| #1831 | WMV, VC-1 + WMA | ```fixme:wmvcore:WMReader_Open (0x35ef1d0)``` |
| #1946 | WMV, VC-1 + WMA | Proton log: ```fixme:wmvcore:WMCreateSyncReader ((nil), 1, 0x37b0478): stub```. |
