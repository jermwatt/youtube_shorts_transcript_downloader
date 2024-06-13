<a href="https://colab.research.google.com/github/jermwatt/youtube_transcript_downloader/blob/main/transcript_downloader_walkthrough.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

# Youtube Shorts Transcripts downloader

Download transcripts for Youtube Shorts by dragging and dropping a text file containing valid Youtube Shorts urls into a simple streamlit app.

This repo illustrates how to use a transcription model to automatically bleep out desired words from an input video.  All processing is performed locally.

It contains a streamlit demo (see below) and detailed walkthrough notebook (see `beep_that_sht_walkthrough.ipynb`).

## Install instructions

To get setup to run the notebook / bleep your own videos / run the strealit demo first install the requirements for this project by pasting the below in your terminal.

```python
pip install -r requirements.txt
```


## Instructions for bleeping your own videos

Start the streamlit demo

```python
python -m streamlit run bleep_that_sht/app.py
```

You will see printouts at the terminal indicating success of the two smallest whisper model downloads - `tiny` and `base`.

Then you can drag and drop your own mp4 (note: only mp4 is accepted) videos into the demo app, define your own bleep_words, and process.

You can download your bleeped video by clicking on the three dots at the bottom right of the bleeped video, and clicking download.