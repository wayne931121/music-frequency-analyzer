# music-frequency-analyzer
audio frequency analyzer in python. detect single midi number and frequency by the time and frame.

# Usage 
```
python analyzer.py a.wav
```
## The analyzer.py will generate the following files
```
PS C:\Users\原神\Desktop\aubio_condaforge_win11_x64> dir

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        2025-10-26   6:52 PM         468241 frequency by frame.csv
-a----        2025-10-26   6:52 PM          57084 frequency by frame.png
-a----        2025-10-26   6:52 PM          84425 frequency by time - details.png
-a----        2025-10-26   6:52 PM         479350 frequency by time.csv
-a----        2025-10-26   6:52 PM          48445 frequency by time.png
-a----        2025-10-26   6:52 PM         274301 midi by frame.csv
-a----        2025-10-26   6:52 PM         285410 midi by time.csv
-a----        2025-10-26   6:52 PM          57232 midi number by frame.png
-a----        2025-10-26   6:52 PM          77311 midi number by time - details.png
-a----        2025-10-26   6:52 PM          50897 midi number by time.png
```

# Demo
https://github.com/wayne931121/music-frequency-analyzer/blob/main/aubio.ipynb (this file is run in colab)

https://github.com/wayne931121/music-frequency-analyzer/blob/main/aubio_condaforge_win11_x64/aubio_condaforge_win11_x64.ipynb

# Result

<img alt="image" src="https://raw.githubusercontent.com/wayne931121/music-frequency-analyzer/refs/heads/main/aubio_condaforge_win11_x64/midi%20number%20by%20time%20-%20details.png" />
<img alt="image" src="https://raw.githubusercontent.com/wayne931121/music-frequency-analyzer/refs/heads/main/aubio_condaforge_win11_x64/frequency%20by%20time%20-%20details.png" />

# Install

Hey, meet install problem with aubio in windows 11 pip? Don't want to build yourself? Try conda forge with python 3.9, take a look at https://github.com/wayne931121/music-frequency-analyzer/tree/main/aubio_condaforge_win11_x64 or read the env file https://github.com/wayne931121/music-frequency-analyzer/blob/main/aubio_condaforge_win11_x64/aubio.yml .

# Reference
https://stackoverflow.com/a/54621604/19470749

https://github.com/aubio/aubio/blob/master/python/demos/demo_pitch.py

https://github.com/aubio/aubio/blob/master/python/demos/demo_waveform_plot.py

# Also See

I find a useful tool:

https://github.com/c-lake/csv-charts

<img alt="image" src="https://github.com/user-attachments/assets/b2ee171b-02e9-45e2-82e1-38d1f82579a5" />
<img alt="image" src="https://github.com/user-attachments/assets/362f457a-a503-4563-9cdf-be2b6eaa79a8" />
<img alt="image" src="https://github.com/user-attachments/assets/fec0e57b-fd1d-421e-bedb-317448d3dedc" />
