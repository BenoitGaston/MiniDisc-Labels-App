# MiniDisc-Labels-Batch-App

A Streamlit App to create automatically [MiniDisc](https://www.minidisc.wiki/).

## Acknowledgments

The template used to create MiniDisc inner labels is coming from [MiniDisc Wiki](https://www.minidisc.wiki/resources/labels).


## Usecases

This project originates from the following need:

* Create MiniDisc labels from a playlist (in `.m3u8` format) using the metadata, in particular the cover artwork, of the songs.

## How to install

Before starting, ensure you have Python 3.8 or higher installed ([Download Python here](https://www.python.org/downloads/)).

### on Linux/Mac run:



```
wget https://github.com/BenoitGaston/MiniDisc-Labels-Batch-App/archive/refs/heads/master.zip
unzip master.zip
cd MiniDisc-Labels-Batch-App-master
chmod +x install.sh
./install.sh
```

### on Windows run:

```
curl https://github.com/BenoitGaston/MiniDisc-Labels-Batch-App/archive/refs/heads/master.zip
unzip master.zip
cd MiniDisc-Labels-Batch-App-master
./install.bat
```

## How to run


1. Create a playlist from an audio software containing the desired albums.
2. Save this playlist using `.m3u8` format with a name that contains the word 'MiniDisc' (`MiniDisc.m3u8`for instance).
3. Run the command:

In terminal navigate to your `MiniDisc-Labels-Batch-App-master` folder and run:

```
source .venv/bin/activate
```

Once your virtual env is activated run:
```
streamlit run minidisc_labels_batch_app.py
```

If the app doesn't start automatically, open your browser and navigate to [http://localhost:8501](http://localhost:8501).

#### Available colors for MiniDIsc labels
```
'black','sky_blue','blue','blue_steel','blue_green',
'navy_blue','blue_turquoise','fushia','gold','green',
'pink','purple_light','purple','orange','red','yellow',
'white','silver'
```

## Apps Screenshots

<img width="651" alt="AppScreenShot" src="https://github.com/user-attachments/assets/6d69d38c-2ee6-4a7e-870a-dbdaf7e62dad" />

## Labels examples

![Printed-MiniDisc-Labels-1](https://github.com/user-attachments/assets/3f5ca080-ac24-4612-a84d-590eeacfc8da)
![Printed-MiniDisc-Labels-2](https://github.com/user-attachments/assets/fba08ad5-a7d4-488a-8c95-430e6f565a05)
![MD-inner-labels-examples](https://github.com/user-attachments/assets/c8d5cb68-64e5-4982-bd96-3b54931a0c7e)
![MD-outer-labels-examples](https://github.com/user-attachments/assets/87745c31-d388-499f-9304-5c387af9c975)
![MD-inner-labels-examples](https://github.com/user-attachments/assets/c8d5cb68-64e5-4982-bd96-3b54931a0c7e)




