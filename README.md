# IzotopeRX_MarkerList_to_Reaper_CSV
This script is convert Izotope RX Marker List text to Reaper CSV Marker List.

__The current version does not work if there is a space in the marker name, so I will upload a fixed version soon. Sorry!__

# Requirements

Python 3.xx
argparse

```
pip install argparse
```

# How to Use

Type Command.

```
python rxtocsv.py -i your_rx_file.txt -o your_converted_file.csv
```

Then Import file.

![IMG](https://github.com/crackerjacques/IzotopeRX_MarkerList_to_Reaper_CSV/blob/main/maker_import.png?raw=true)


# rxtocsv-ez.py

This is easy version but run in only Windows.

first, install easygui

```
pip install easygui
```

Then type this command.

```
python rxtocsv-ez.py 
```

Select input text file and output csv dir.

If you want to run it by double-clicking, you can create a Powershell script or bat file.

open notepad then write
```
python rxtocsv-ez.py 
exit
```

then savefile and change extension .txt to bat


