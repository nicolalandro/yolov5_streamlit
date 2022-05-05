[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/nicolalandro/yolov5_streamlit/main)

# Yolov5 Streamlit
This codebase create a realtime web demo with streamlit. As you can see from the streamlit deploy, if you do not have a GPU you cannot be realtime.

## Develop
```
python3.8 -m venv venv
source venv/bin/activate
# or on fish shell
source venv/bin/activate.fish

pip install -r requirements.txt

python -m streamlit run app.py
```

# References
* [streamlit](https://streamlit.io/): library for web demo
* [streamlit_webrtc](https://github.com/whitphx/streamlit-webrtc): to use webcam from browser on stramlit
* [yolov5](https://github.com/ultralytics/yolov5): trained model
