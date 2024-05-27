# Resemble’s AI voice generator
Resemble’s AI voice generator lets you create realistic human–like voiceovers in seconds.

<br>

## ⚙️ Usage:
```python
if __name__ == "__main__":
    pod = VoicePod('This is a Sample Text')
    print(pod.Generate()) # Returns uuid-output.mp3 path
```

<br>

## 📚 Functions:
#### `VoicePod.Generate`
- Requests to origin using query.
#### `VoicePod.GetCaptcha2Token`
- Get hidden captcha2 token using captcha URL.
#### `VoicePod.BytestoMp3(content)`
- Convert bytes to mp3 using wave (22050 frame rate) .

<br>

## 🎵 Sample Audio:
https://github.com/Vauth/voicepod/assets/122077080/901fa0ff-4e8f-46e4-966d-4c7316279e33
