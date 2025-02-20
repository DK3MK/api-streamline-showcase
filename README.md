# API Streamline Documentation 🚀
[API Streamline]: https://api-streamline-pro.vercel.app/

Welcome to the **[API Streamline]** documentation! This guide provides simple examples for using our API, which is organized by categories and supports two main response types: JSON data and direct image output.

## Response Types 📤

1. **JSON**: Endpoints returning JSON data provide structured information.  
2. **Image**: Endpoints may return images directly for immediate display.

> **Note:** For endpoints with extensive JSON responses, we use a collapsible section (click the arrow below) to keep the documentation clean and manageable.

---

## Categories 📚

Our API is divided into six categories, each serving different functionalities:

## **1. Ai** 🤖
### **ChatGPT**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/chatgpt?prompt=hi&userid=123"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "chatgpt": "Hello! How can I assist you today?"
}
```
</details>

### **Llama Flare**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/llama-flare?prompt=hi&system=Virtual+Assistant"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "llama": "Hi! It's nice to meet you. Is there something I can help you with or would you like to chat?"
}
```
</details>

### **Speech2Text**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/speech2text?url=https://github.com/DK3MK/worker-bot/raw/refs/heads/main/mp3/test-myapi.wav"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "data": [
    {
      "text": "Hello, it is a good day for me to teach you the sound of my voice. You have learned what I look like now you can hear what I sound like. The sound of my voice will help the transcription service to recognize my unique voice in the future. Training will provide a better experience with greater accuracy when talking or dictating. Thank you and goodbye.",
      "word_count": 66,
      "vtt": "WEBVTT\n\n00.580 --> 01.460\nHello, it is a good\n\n01.460 --> 02.400\nday for me to teach\n\n02.400 --> 03.440\nyou the sound of my\n\n03.440 --> 04.740\nvoice. You have learned what\n\n04.740 --> 05.680\nI look like now you\n\n05.680 --> 06.500\ncan hear what I sound\n\n06.500 --> 08.020\nlike. The sound of my\n\n08.020 --> 09.140\nvoice will help the transcription\n\n09.140 --> 10.620\nservice to recognize my unique\n\n10.620 --> 12.700\nvoice in the future. Training\n\n12.700 --> 14.060\nwill provide a better experience\n\n14.060 --> 15.580\nwith greater accuracy when talking\n\n15.580 --> 17.280\nor dictating. Thank you and\n\n17.280 --> 18.160\ngoodbye.",
      "words": [
        {
          "word": "Hello,",
          "start": 0.5799999833106995,
          "end": 1
        },
        {
          "word": "it",
          "start": 1,
          "end": 1.100000023841858
        },
        {
          "word": "is",
          "start": 1.100000023841858,
          "end": 1.2200000286102295
        },
        {
          "word": "a",
          "start": 1.2200000286102295,
          "end": 1.3200000524520874
        },
        {
          "word": "good",
          "start": 1.3200000524520874,
          "end": 1.4600000381469727
        },
        {
          "word": "day",
          "start": 1.4600000381469727,
          "end": 1.659999966621399
        },
        {
          "word": "for",
          "start": 1.659999966621399,
          "end": 1.8600000143051147
        },
        {
          "word": "me",
          "start": 1.8600000143051147,
          "end": 1.9800000190734863
        },
        {
          "word": "to",
          "start": 1.9800000190734863,
          "end": 2.0999999046325684
        },
        {
          "word": "teach",
          "start": 2.0999999046325684,
          "end": 2.4000000953674316
        },
        {
          "word": "you",
          "start": 2.4000000953674316,
          "end": 2.5999999046325684
        },
        {
          "word": "the",
          "start": 2.5999999046325684,
          "end": 2.819999933242798
        },
        {
          "word": "sound",
          "start": 2.819999933242798,
          "end": 3.0399999618530273
        },
        {
          "word": "of",
          "start": 3.0399999618530273,
          "end": 3.2799999713897705
        },
        {
          "word": "my",
          "start": 3.2799999713897705,
          "end": 3.440000057220459
        },
        {
          "word": "voice.",
          "start": 3.440000057220459,
          "end": 4.179999828338623
        },
        {
          "word": "You",
          "start": 4.179999828338623,
          "end": 4.239999771118164
        },
        {
          "word": "have",
          "start": 4.239999771118164,
          "end": 4.360000133514404
        },
        {
          "word": "learned",
          "start": 4.360000133514404,
          "end": 4.519999980926514
        },
        {
          "word": "what",
          "start": 4.519999980926514,
          "end": 4.739999771118164
        },
        {
          "word": "I",
          "start": 4.739999771118164,
          "end": 4.860000133514404
        },
        {
          "word": "look",
          "start": 4.860000133514404,
          "end": 5.059999942779541
        },
        {
          "word": "like",
          "start": 5.059999942779541,
          "end": 5.28000020980835
        },
        {
          "word": "now",
          "start": 5.28000020980835,
          "end": 5.539999961853027
        },
        {
          "word": "you",
          "start": 5.539999961853027,
          "end": 5.679999828338623
        },
        {
          "word": "can",
          "start": 5.679999828338623,
          "end": 5.840000152587891
        },
        {
          "word": "hear",
          "start": 5.840000152587891,
          "end": 6
        },
        {
          "word": "what",
          "start": 6,
          "end": 6.139999866485596
        },
        {
          "word": "I",
          "start": 6.139999866485596,
          "end": 6.260000228881836
        },
        {
          "word": "sound",
          "start": 6.260000228881836,
          "end": 6.5
        },
        {
          "word": "like.",
          "start": 6.5,
          "end": 7.400000095367432
        },
        {
          "word": "The",
          "start": 7.400000095367432,
          "end": 7.5
        },
        {
          "word": "sound",
          "start": 7.5,
          "end": 7.71999979019165
        },
        {
          "word": "of",
          "start": 7.71999979019165,
          "end": 7.880000114440918
        },
        {
          "word": "my",
          "start": 7.880000114440918,
          "end": 8.020000457763672
        },
        {
          "word": "voice",
          "start": 8.020000457763672,
          "end": 8.34000015258789
        },
        {
          "word": "will",
          "start": 8.34000015258789,
          "end": 8.460000038146973
        },
        {
          "word": "help",
          "start": 8.460000038146973,
          "end": 8.640000343322754
        },
        {
          "word": "the",
          "start": 8.640000343322754,
          "end": 8.779999732971191
        },
        {
          "word": "transcription",
          "start": 8.779999732971191,
          "end": 9.140000343322754
        },
        {
          "word": "service",
          "start": 9.140000343322754,
          "end": 9.600000381469727
        },
        {
          "word": "to",
          "start": 9.600000381469727,
          "end": 9.760000228881836
        },
        {
          "word": "recognize",
          "start": 9.760000228881836,
          "end": 10.119999885559082
        },
        {
          "word": "my",
          "start": 10.119999885559082,
          "end": 10.319999694824219
        },
        {
          "word": "unique",
          "start": 10.319999694824219,
          "end": 10.619999885559082
        },
        {
          "word": "voice",
          "start": 10.619999885559082,
          "end": 10.960000038146973
        },
        {
          "word": "in",
          "start": 10.960000038146973,
          "end": 11.239999771118164
        },
        {
          "word": "the",
          "start": 11.239999771118164,
          "end": 11.380000114440918
        },
        {
          "word": "future.",
          "start": 11.380000114440918,
          "end": 12.5
        },
        {
          "word": "Training",
          "start": 12.5,
          "end": 12.699999809265137
        },
        {
          "word": "will",
          "start": 12.699999809265137,
          "end": 12.920000076293945
        },
        {
          "word": "provide",
          "start": 12.920000076293945,
          "end": 13.199999809265137
        },
        {
          "word": "a",
          "start": 13.199999809265137,
          "end": 13.380000114440918
        },
        {
          "word": "better",
          "start": 13.380000114440918,
          "end": 13.579999923706055
        },
        {
          "word": "experience",
          "start": 13.579999923706055,
          "end": 14.0600004196167
        },
        {
          "word": "with",
          "start": 14.0600004196167,
          "end": 14.279999732971191
        },
        {
          "word": "greater",
          "start": 14.279999732971191,
          "end": 14.5
        },
        {
          "word": "accuracy",
          "start": 14.5,
          "end": 15.039999961853027
        },
        {
          "word": "when",
          "start": 15.039999961853027,
          "end": 15.260000228881836
        },
        {
          "word": "talking",
          "start": 15.260000228881836,
          "end": 15.579999923706055
        },
        {
          "word": "or",
          "start": 15.579999923706055,
          "end": 15.819999694824219
        },
        {
          "word": "dictating.",
          "start": 15.819999694824219,
          "end": 16.68000030517578
        },
        {
          "word": "Thank",
          "start": 16.68000030517578,
          "end": 16.799999237060547
        },
        {
          "word": "you",
          "start": 16.799999237060547,
          "end": 17.020000457763672
        },
        {
          "word": "and",
          "start": 17.020000457763672,
          "end": 17.280000686645508
        },
        {
          "word": "goodbye.",
          "start": 17.280000686645508,
          "end": 18.15999984741211
        }
      ]
    }
  ]
}
```
</details>

### **Text2Art**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/text2art?text=Anime"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "data": [
    {
      "img_url": "https://image.lexica.art/full_jpg/5166d5bc-e04a-4ca7-9970-3241bc2c8873",
      "prompt": "A black and white picture for coloring of an anime girl in long hair, in the style of subversive appropriation, blink - and - you - miss - it detail, bold chromaticity, the new fauves, charming characters, , hurufiyya,"
    },
    {
      "img_url": "https://image.lexica.art/full_jpg/ee4c71cf-a79a-44bf-878d-6dc060192b82",
      "prompt": "guy 18 years old. Shoulder length black curly hair. Black iris of the eyes. The face is beautiful, but not flashy. anime reskin style"
    },
    {
      "img_url": "https://image.lexica.art/full_jpg/68b6527b-82c0-4605-87d1-b441e2c821f3",
      "prompt": "beautiful simple girl with black hair and big eyes anime style"
    },
    {
      "img_url": "https://image.lexica.art/full_jpg/742609b2-58aa-47a4-a13f-a7e00297cd49",
      "prompt": "Nen user in hunter x Hunter style"
    },
    {
      "img_url": "https://image.lexica.art/full_jpg/d8388fcd-1b6a-4aad-a53e-4cd9295a32aa",
      "prompt": "lady 20 years old. dark brown straight hair. green eyes. height 176. anime reskin style. impudent"
    },
    {
      "img_url": "https://image.lexica.art/full_jpg/b22582ef-91b0-48e3-9794-ddaddabaadad",
      "prompt": "A black and white picture for coloring of an anime girl in long hair, in the style of subversive appropriation, blink - and - you - miss - it detail, bold chromaticity, the new fauves, charming characters, , hurufiyya,"
    },
    {
      "img_url": "https://image.lexica.art/full_jpg/860f5df2-1857-4b64-ad56-619d88f63795",
      "prompt": "girl 17 years old. dark skin. white straight hair. black eyes. fragile figure. height 173. anime reskin style."
    },
    {
      "img_url": "https://image.lexica.art/full_jpg/6f236ec3-f0f7-45e3-ba4d-7002923e5b83",
      "prompt": "Une fille avec un sèche-cheveux dans les mains dans le style 90’s anime vintage"
    },
    {
      "img_url": "https://image.lexica.art/full_jpg/ebdd5c3f-eb6c-4018-978e-4caa6312c191",
      "prompt": "woman 18 years old. Shoulder length black straight hair. Black eye. The face is beautiful, but not flashy. anime reskin style"
    }
  ]
}
```
</details>

### **Google Gemma**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/google-gemma?prompt=hi"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "gemma": "Hi! 👋 It's great to hear from you. How can I help you today? 😊"
}
```
</details>

### **Chat Chars**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/chat-chars?prompt=hi&userid=123&char=Play+as+Elon+Musk+to+answer"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "char": "Hello! How can I help you today?"
}
```
</details>

### **DeepAI Text2Img**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/deepai-text2img?text=cyberpunk+cat"
```

<details> <summary>🔽 Image Response</summary>

```
Output: Direct Image Output.
```

</details>

### **Picasso Pharaonic**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/picasso-pharaonic?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg"
```

<details> <summary>🔽 Image Response</summary>

```
Output: Direct Image Output.
```

</details>

### **Picasso Professional**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/picasso-professional?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg"
```

<details> <summary>🔽 Image Response</summary>

```
Output: Direct Image Output.
```

</details>

### **Picasso Warrior**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/picasso-warrior?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg"
```

<details> <summary>🔽 Image Response</summary>

```
Output: Direct Image Output.
```

</details>

### **Picasso Cyborg**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/picasso-cyborg?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg"
```

<details> <summary>🔽 Image Response</summary>

```
Output: Direct Image Output.
```

</details>

### **Picasso Abstract**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/picasso-abstract?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg"
```

<details> <summary>🔽 Image Response</summary>

```
Output: Direct Image Output.
```

</details>

### **Picasso Oilpainting**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/picasso-oilpainting?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg"
```

<details> <summary>🔽 Image Response</summary>

```
Output: Direct Image Output.
```

</details>

### **Picasso Palestinian**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/ai/picasso-palestinian?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg"
```

<details> <summary>🔽 Image Response</summary>

```
Output: Direct Image Output.
```

</details>

## **2. Tools ⬇️**
### **Google Translate**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/tools/google-translate?text=Hello!&to=ar"
```

<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "translate": [
    {
      "translated_text": "مرحبًا!",
      "from": "eng",
      "to": "ara"
    }
  ]
}
```

</details>

### **Web Scraper**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/tools/web-scraper?url=https://api-streamline-pro.vercel.app/"
```

<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "scrap": [
    {
      "imgs": [],
      "links": [],
      "txt": "API Streamline\n\nAPI Streamline\n\nWelcome to API Streamline\n\nExplore a wide range of APIs across various categories.\n\n\nFeatured APIs\n\nName Method Category Parameters Action \n\n\n\n\n",
      "search": [
        "API Streamline",
        "API Streamline",
        "Welcome to API Streamline",
        "Explore a wide range of APIs across various categories.",
        "Featured APIs",
        "Name Method Category Parameters Action "
      ],
      "cq": ""
    }
  ]
}
```

</details>

### **Get Source Code**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/tools/get-code?url=https://api-streamline-pro.vercel.app/"
```

<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "source": [
    {
      "method": "GET",
      "urlSupplier": "https://api-streamline-pro.vercel.app/",
      "redirectedUrlSupplier": null,
      "pageSource": "<html lang=\"en\"><head>\n    <meta charset=\"UTF-8\">\n    <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">\n    <title>API Streamline</title>\n    <link rel=\"icon\" href=\"images/streamline.png\" type=\"image/x-icon\">\n    <link href=\"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css\" rel=\"stylesheet\">\n    <link rel=\"stylesheet\" href=\"styles.css\">\n</head>\n<body>\n    <header class=\"header\">\n        <div class=\"header-left\">\n            <h1>API Streamline</h1>\n        </div>\n    </header>\n\n    <main class=\"main-content\">\n        <div class=\"welcome-text\">\n            <h1>Welcome to API Streamline</h1>\n            <p>Explore a wide range of APIs across various categories.</p>\n        </div>\n\n        <div class=\"categories\"><div class=\"category-card\" id=\"ai-card\">\n            <div class=\"category-icon\">\n                <i class=\"fas fa-robot\"></i>\n            </div>\n            <div class=\"category-info\">\n                <h3>Ai</h3>\n                <p>8 APIs</p>\n            </div>\n        </div><div class=\"category-card\" id=\"tools-card\">\n            <div class=\"category-icon\">\n                <i class=\"fas fa-tools\"></i>\n            </div>\n            <div class=\"category-info\">\n                <h3>Tools</h3>\n                <p>2 APIs</p>\n            </div>\n        </div><div class=\"category-card\" id=\"download-card\">\n            <div class=\"category-icon\">\n                <i class=\"fas fa-download\"></i>\n            </div>\n            <div class=\"category-info\">\n                <h3>Downloader</h3>\n                <p>5 APIs</p>\n            </div>\n        </div><div class=\"category-card\" id=\"search-card\">\n            <div class=\"category-icon\">\n                <i class=\"fas fa-search\"></i>\n            </div>\n            <div class=\"category-info\">\n                <h3>Search</h3>\n                <p>6 APIs</p>\n            </div>\n        </div></div>\n\n        <div class=\"featured-section\" id=\"featured-section\">\n            <h2 class=\"featured-header\">Featured APIs</h2>\n            <table class=\"api-table\" id=\"api-table\">\n                <thead>\n                    <tr>\n                        <th>Name</th>\n                        <th>Method</th>\n                        <th>Category</th>\n                        <th>Parameters</th>\n                        <th>Action</th>\n                    </tr>\n                </thead>\n                <tbody>\n                    <!-- سيتم ملء هذا الجدول ديناميكيًا باستخدام JavaScript -->\n                </tbody>\n            </table>\n        </div>\n    </main>\n\n    <footer>\n        <div class=\"footer-bottom\">\n            <p>© 2025 API Streamline. All rights reserved.</p>\n        </div>\n    </footer>\n\n    <script src=\"script.js\"></script>\n\n</body></html>"
    }
  ]
}
```

</details>

### **DeepAi RemBg**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/tools/rembg?url=https://api-streamline.vercel.app/anything/darkman.jpg"
```

<details> <summary>🔽 Image Response</summary>

```
Output: Direct Image Output.
```

</details>

## **3. Downloader ⬇️**
### **Download From TikTok**:

- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/downloader/tiktok?url=https://vt.tiktok.com/ZS2tqxmeX/"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Video fetched successfully! 🎥",
  "download": [
    {
      "id": "7406264589345656082",
      "region": "OM",
      "title": "شيخنا الخليلي آية من آيات الله 😍",
      "cover": "https://www.tikwm.com/video/cover/7406264589345656082.webp",
      "duration": 69,
      "play": "https://www.tikwm.com/video/media/play/7406264589345656082.mp4",
      "wmplay": "https://www.tikwm.com/video/media/wmplay/7406264589345656082.mp4",
      "hdplay": "https://www.tikwm.com/video/media/hdplay/7406264589345656082.mp4",
      "size": 2698609,
      "wm_size": 4693648,
      "hd_size": 33187295,
      "music": "https://www.tikwm.com/video/music/7406264589345656082.mp3",
      "music_info": {
        "id": "7406264649374534417",
        "title": "original sound - mu98k",
        "play": "https://sf16-ies-music-sg.tiktokcdn.com/obj/tiktok-obj/7406264647231310608.mp3",
        "author": "مختار|Mukhtar",
        "original": true,
        "duration": 69,
        "album": ""
      },
      "play_count": 225420,
      "digg_count": 7674,
      "comment_count": 324,
      "share_count": 710,
      "download_count": 1664,
      "collect_count": 942,
      "create_time": 1724405354,
      "anchors": null,
      "anchors_extras": "",
      "is_ad": false,
      "commerce_info": {
        "adv_promotable": false,
        "auction_ad_invited": false,
        "branded_content_type": 0,
        "with_comment_filter_words": false
      },
      "commercial_video_info": "",
      "item_comment_settings": 0,
      "mentioned_users": "",
      "author": {
        "id": "6940657058237072390",
        "unique_id": "mu98k",
        "nickname": "مختار|Mukhtar",
        "avatar": "https://www.tikwm.com/video/avatar/7406264589345656082.jpeg"
      }
    }
  ]
}
```
</details>


### **Download From YouTube**:
- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/downloader/youtube?url=https://www.youtube.com/watch?v=3gMhxs51lhI/"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Video fetched successfully! 🎥",
  "download": [
    {
      "url_video": {
        "itag": 18,
        "url": "https://redirector.googlevideo.com/videoplayback?expire=1740052918&ei=VsW2Z9fXDP-J6dsPi-_MqAQ&ip=176.1.216.8&id=o-AIv-nR7ZLuatEKMwivQ_S5BX-8net07Z9E9_vHzWXINl&itag=18&source=youtube&requiressl=yes&xpc=EgVo2aDSNQ%3D%3D&met=1740031318%2C&mh=8W&mm=31%2C29&mn=sn-uxax4vopj5qx-q0n6%2Csn-4g5e6nsr&ms=au%2Crdu&mv=m&mvi=5&pl=26&rms=au%2Cau&initcwndbps=1872500&bui=AUWDL3ye6i4FWl74oBHiChyJptwstXhYGyaA1Ai5C_wH_WAEw3R6kFZiTH43dJ1TDEXH1KV-D-ypRVlB&spc=RjZbSdbRoWBo0iNpCr6MIi-m7qYhAWbEr67Gqs1N1lgtpRaNkC-U&vprv=1&svpuc=1&mime=video%2Fmp4&ns=TL_zJwVJuO6tq_GbdBli_bIQ&rqh=1&cnr=14&ratebypass=yes&dur=123.576&lmt=1733913031672355&mt=1740030777&fvip=4&fexp=51326932%2C51355912&c=WEB&sefc=1&txp=6208224&n=anfVUdpFzP5fPA&sparams=expire%2Cei%2Cip%2Cid%2Citag%2Csource%2Crequiressl%2Cxpc%2Cbui%2Cspc%2Cvprv%2Csvpuc%2Cmime%2Cns%2Crqh%2Ccnr%2Cratebypass%2Cdur%2Clmt&sig=AJfQdSswRQIhAIL7DQWBO2AiTWXCeUuhWuRkHF4Xs9uKD0MuamHeu_2AAiBKq5refsR8c2WLUOT9mCfwlZ42exPst0EtXK5G2ziumQ%3D%3D&lsparams=met%2Cmh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Crms%2Cinitcwndbps&lsig=AGluJ3MwRAIgbEt9TUV0TF46ZQy_7YeFrKmHGaSAVMVs1SZ7pw-iEdECIB-VFCYPD63KzS2Pw8clY8XzPk-AZaYqu-V9yaEhnYcL&pot=MnQbSf3t4AtusRt1qaf9DpY_-IAZea09LbFjYQZWZp-EXMgGNXWWmGtoGnF2W9WNYQKSscDpTZCDi2yqVIktsdzHGgsI6yh4ZuRtDAQjAJeUvd9bDBtJS-PAeRu4nGsDaJaqL9p5Q-yUC42e3hHyZzGS6UCPdQ==",
        "mimeType": "video/mp4; codecs=\"avc1.42001E, mp4a.40.2\"",
        "bitrate": 548282,
        "width": 640,
        "height": 280,
        "lastModified": "1733913031672355",
        "quality": "medium",
        "fps": 25,
        "qualityLabel": "360p",
        "projectionType": "RECTANGULAR",
        "audioQuality": "AUDIO_QUALITY_LOW",
        "approxDurationMs": "123576",
        "audioSampleRate": "44100",
        "audioChannels": 2
      },
      "title": "لقطات كلاسيكية قصيرة | FREE FIRE.",
      "channelTitle": "أڪشن | ACTION FF",
      "description": "free fire tik tok,\nfree fire live,\nfree fire max,\nfree fire song,\nfree fire maroc,\nfree fire hack,\nfree fire exe,\nfree fire يوتيوب,\nfree fire وايت,\nfree fire و pubg,\nfree fire وقت انتهاء الصيانة,\nfree fire وولفرا,\nfree fire ادر واربح,\nfree fire gameplay,\nfree fire هياتو,\nfree fire هيروشيما,\nfree fire هيد شوت,\nfree fire هرشم,\nfree fire هاند كام,\nfree fire نوب,\nfree fire نينجا,\nfree fire نصائح,\nfree fire نوب vs محترف,\nfree fire نفس الوقت,\nfree fire نسخة المطورين,\nfree fire مباشر,\nfree fire مضحك مغربي,\nfree fire مكافحة,\nfree fire مهكرة 2020,\nfree fire مهكرة اخر اصدار,\nfree fire مع اغنية حماسية,\nfree fire م,\nfree fire لعبة,\nfree fire للمبتدئين,\nfree fire للكمبيوتر,\nfree fire لعب,\nfree fire لقطات مضحكة تحشيش,\nجلد free fire,\nfree fire كلاش سكواد,\nfree fire كيف تحصل على الجواهر,\nfree fire كيف تهكر,\nfree fire كود,\nfree fire كلاش سكواد المصنف,\nfree fire كيف تحصل على رقصة,\nfree fire قناة,\nfree fire قصة حب,\nfree fire قنوات,\nfree fire قصص,\nfree fire قصة هياتو,\nfree fire فري فاير,\nfree fire فاكتوري,\nfree fire فتح صناديق,\nfree fire فاير باس المجاني,\nقلتش free fire,\nغنيت free fire,\nغزاوي free fire,\nfree fire علي عمر,\nfree fire عكاش\nfree fire اغنية,\nfree fire أفضل لاعب,\nfree fire أهل مصر 2020,\nfree fire أغاني,\nfree fire أحسن لاعب,\nfree fire أسرار,\nfree fire أرض الشتاء,\nfree fire اللوك,\nأيفان /free fire,\nأيوب free fire,\nإعدادات الهيدشوت free fire للايفون,\nأيمن free fire,\nfree fire للكمبيوتر,\nfree fire للكمبيوتر تحميل,\nfree fire كيف تحصل على الجواهر,\nfree fire كيف تهكر,\nfree fire كيف تحصل على رقصة,\nfree fire كيف تصبح سريع في الثلج,\nfree fire كيف تصبح محترف,\nfree fire كيف تغير اسمك,\nfree fire كيفية لعب,\nfree fire كيفية الحصول على المكعب السحري,\nfree fire لماذا نحن هنا,\nfree fire ماسونية,\nfree fire ماسوني,\nfree fire ما الجديد,\nfree fire ماكرو,\nfree fire ماجيك كيوب,\nfree fire ما هو عيش الغراب,\nfree fire مالك مخلوع,\nنور مار free fire,\nfree fire منظور الشخص الاول,\nfree fire من البداية,\nfree fire من نوب الى محترف,\nfree fire max من ميديا فاير,\nfree fire من الصفر,\nfree fire من الاول,\nfree fire الهروب من السجن\ninfinix hot 9 فري فاير,\nالموسم 9 فري فاير,\nشاومي نوت 9 فري فاير,\nفاير باس 9 فري فاير,\nاعدادات ريدمي 9 فري فاير,\nريدمي نوت 9 فري فاير,\nتجربة ريدمي 9 فري فاير,\nريدمي 9 فري فاير,\nمتجر التخفيضات فري فاير 90,\nمتجر التخفيضات فري فاير 99,\nفري فاير 90 fps,\nفري فاير 9999,\nفري فاير 99999,\nفري فاير 9999 جوهرة,\nفري فاير 999,\nفري فاير 99,\ninfinix hot 8 فري فاير,\nاعدادات ايفون 8 فري فاير,\nفاير باس 8 فري فاير,\nشاومي نوت 8 فري فاير,\nايفون 8 فري فاير,\nريدمي 8 فري فاير,\nاقوى حساب فري فاير لفل 80,\nاعدادات ريدمي 8 فري فاير,\nريدمي نوت 8 فري فاير,\nفاير باس فري فاير 8,\nبليز لا فري فاير 8,\nفري فاير 8 اصابع,\nفري فاير 8 سموحه,\nxiaomi redmi 7 فري فاير,\ninfinix note 7 فري فاير,\nفاير باس 7 فري فاير,\nريدمي نوت 7 فري فاير,\nالحر 7 فري فاير,\n7ashish فري فاير,\nايباد 7 فري فاير,\nاعدادات ايفون 7 فري فاير,\nايفون 7 فري فاير,\nبليز لا فري فاير 7,\nفعالية الإنتحار فري فاير 7liwat,\nمقلب الطفل فري فاير 7liwat,\nفري فاير 7liwat,\nيوم 6 فري فاير,\nهاتف ريلمي 6 فري فاير,\nايباد 6 فري فاير,\nتسريع الايفون 6 فري فاير,\nفاير باس 6 فري فاير,\nريلمي 6 فري فاير,\nاعدادات ايفون 6 فري فاير,\nايفون 6 فري فاير,\nاعدادات الايفون فري فاير 6s,\nتسريبات فري فاير 6 سبتمبر,\nتسريبات 6 سبتمبر فري فاير,\nبليز لا فري فاير 6,\nاعدادات فري فاير 6 اصابع\nفري فاير هل وايت هكر,\nفري فاير هلا والله,\nفري فاير هل الفاير باس القادم مجانا,\nفري فاير هل حرام,\nفري فاير هل هي خطيرة,\nفري فاير هل الفاير باس القادم مجاني,\nفري فاير هل سيعود سكن الجوكر,\nفري فاير هل هي حرام,\nفري فاير من دون نت,\nفري فاير من اول فاير باس,\nفري فاير من نوب الى محترف,\nفري فاير من اول ما نزلت,\nفري فاير من البداية,\nفري فاير من زمان,\nفري فاير من السيزون الاول,\nفري فاير من الفاير باس الاول الى الاخير,\nفري فاير متى ينزل التحديث الجديد,\nفري فاير من متجر التخفيضات,\nفري فاير متى ينتهي التحديث,\nفري فاير متى نزلت\nفري فاير متى تنتهي الصيانة,\nفري فاير متى ينزل المتجر الغامض,\nفري فاير متى يفتح الجلاد,\nفري فاير متى التحديث الجديد,\nماذا يوجد في القنابل فري فاير,\nفري فاير ماذا يقول اللوك,\nفري فاير ماذا تفعل,\nفري فاير ماذا يوجد بعد الهيرو,\nفري فاير ماذا يوجد داخل القنبلة,\nفري فاير ماذا تفعل القطة,\nفري فاير ماجيك كيوب مجانا,\nفري فاير مان,\nفري فاير ماكرو,\nفري فاير مالك,\nفري فاير ماذا يوجد داخل الخزنه\n#freefire_glitch #freefire_hack #freefirenews #freefirehighlights #freefiremontage #freefirehacker #freefire_bestplayer #freefiretiktok #freefireفري_فاير #freefireاقوا #freefire0507 #freefire12thpiratetreasurechestlocation #freefire13decemberpiratetreasureboxlocation #freefire19decemberpiratetreasureboxlocation #freefire12decemberpiratetreasureboxlocation #freefire15decemberpiratetreasureboxlocation #freefire16decemberpiratetreasureboxlocation #freefire17decemberpiratetreasureboxlocation #freefire14decemberpiratetreasureboxlocation #freefire2020 #freefire200 #freefire2308 #freefire31thpiratetreasurechestlocation #freefire30daypiratetreasurelocation #freefire3rdanniversary\n#freefire #freefiremax #freefireshorts #فري_فاير #فريفاير #freefirelovers #اكسبلور #لايك",
      "thumbnail": {
        "url": "https://i.ytimg.com/vi_webp/3gMhxs51lhI/maxresdefault.webp",
        "width": 1920,
        "height": 1080
      },
      "publishvideo": "2024-09-28T18:53:14-07:00",
      "category": "Gaming"
    }
  ]
}
```
</details>

## **4. Search ⬇️**
### **Google Search**:

- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/search/google?query=فلسطين&lang=ar"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "google": [
    {
      "title": "فلسطين - ويكيبيديا",
      "htmlTitle": "<b>فلسطين</b> - ويكيبيديا",
      "snippet": "فِلَسْطِين (بالعبرية: פלשתינה أو פלסטין حسب السياق، باليونانية: Παλαιστίνη) هي المنطقة الجغرافية الواقعة جنوب شرق البحر المتوسط حتى وادي الأردن، وفي بعض ...",
      "htmlSnippet": "فِلَسْطِين (بالعبرية: פלשתינה أو פלסטין حسب السياق، باليونانية: Παλαιστίνη) هي المنطقة الجغرافية الواقعة جنوب شرق البحر المتوسط حتى وادي الأردن، وفي بعض ...",
      "link": "https://ar.wikipedia.org/wiki/%D9%81%D9%84%D8%B3%D8%B7%D9%8A%D9%86",
      "displayLink": "ar.wikipedia.org"
    },
    {
      "title": "دولة فلسطين - ويكيبيديا",
      "htmlTitle": "دولة <b>فلسطين</b> - ويكيبيديا",
      "snippet": "فِلَسْطِين (رسميًا: دَوْلَةُ فِلَسْطِين) هي بحكم القانون دولة ذات سيادة في غرب آسيا، وتحكمها رسميًا منظمة التحرير الفلسطينية وتطالب بالضفة الغربية وقطاع غزة.",
      "htmlSnippet": "فِلَسْطِين (رسميًا: دَوْلَةُ فِلَسْطِين) هي بحكم القانون دولة ذات سيادة في غرب آسيا، وتحكمها رسميًا منظمة التحرير ال<b>فلسطين</b>ية وتطالب بالضفة الغربية وقطاع غزة.",
      "link": "https://ar.wikipedia.org/wiki/%D8%AF%D9%88%D9%84%D8%A9_%D9%81%D9%84%D8%B3%D8%B7%D9%8A%D9%86",
      "displayLink": "ar.wikipedia.org"
    },
    {
      "title": "أخبار فلسطين اليوم - الجزيرة نت",
      "htmlTitle": "أخبار <b>فلسطين</b> اليوم - الجزيرة نت",
      "snippet": "قتلت قوات الاحتلال الإسرائيلي اليوم الأربعاء 3 فلسطينيين بعد محاصرة منزل بمخيم الفارعة، في وقت دوت انفجارات عنيفة داخل مخيم طولكرم تزامناً مع استمرار العدوان على ...",
      "htmlSnippet": "قتلت قوات الاحتلال الإسرائيلي اليوم الأربعاء 3 <b>فلسطين</b>يين بعد محاصرة منزل بمخيم الفارعة، في وقت دوت انفجارات عنيفة داخل مخيم طولكرم تزامناً مع استمرار العدوان على ...",
      "link": "https://www.aljazeera.net/palestine/",
      "displayLink": "www.aljazeera.net"
    }
  ]
}
```
</details>

### **Google Search V2**:

- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/search/google-v2?query=فلسطين"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "google": [
    {
      "position": 1,
      "url": "https://ar.wikipedia.org/wiki/%D9%81%D9%84%D8%B3%D8%B7%D9%8A%D9%86",
      "title": "فلسطين - ويكيبيديا",
      "description": "فِلَسْطِين (بالعبرية: פלשתינה أو פלסטין حسب السياق، باليونانية: Παλαιστίνη) هي المنطقة الجغرافية الواقعة جنوب شرق البحر المتوسط حتى وادي الأردن، وفي بعض ..."
    },
    {
      "position": 2,
      "url": "https://en.wikipedia.org/wiki/Palestine",
      "title": "Palestine - Wikipedia",
      "description": "Palestine, officially the State of Palestine, is a country in the Southern Levant region of West Asia. Recognized by a majority of UN member states, ..."
    },
    {
      "position": 3,
      "url": "https://www.aljazeera.net/palestine/",
      "title": "أخبار فلسطين اليوم - الجزيرة نت",
      "description": "قتلت قوات الاحتلال الإسرائيلي اليوم الأربعاء 3 فلسطينيين بعد محاصرة منزل بمخيم الفارعة، في وقت دوت انفجارات عنيفة داخل مخيم طولكرم تزامناً مع استمرار العدوان على ..."
    }
  ]
}
```
</details>

### **Google Search Img**:

- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/search/google-img?query=علم+فلسطين"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "images": [
    {
      "title": "صور علم فلسطين أجمل صور العلم الفلسطيني - عالم الصور",
      "image": "https://alamphoto.com/wp-content/uploads/2018/01/Palestine-flag-1.jpg",
      "thumbnail": "https://tse2.mm.bing.net/th?id=OIP.E7xAxIvUF2FJ3aD0ZOkFdAHaDt&pid=Api",
      "url": "https://alamphoto.com/images/صور-علم-فلسطين-أجمل-صور-العلم-الفلسطين/",
      "height": 960,
      "width": 1920,
      "source": "Bing"
    },
    {
      "title": "اجمل الصور لعلم فلسطين رمز العزة والصمود",
      "image": "https://pic.i7lm.com/wp-content/uploads/2020/05/3-8-1536x985.jpg",
      "thumbnail": "https://tse3.explicit.bing.net/th?id=OIP.tfzxStiiXhImMKK6GCMWGwHaEv&pid=Api",
      "url": "https://pic.i7lm.com/اجمل-الصور-لعلم-فلسطين/",
      "height": 985,
      "width": 1536,
      "source": "Bing"
    },
    {
      "title": "محمد رمضان يشارك جمهوره صورة العلم الفلسطيني بعد أزمته الأخيرة - اليوم ...",
      "image": "https://img.youm7.com/ArticleImgs/2020/11/23/660566-علم-فلسطين.jpg",
      "thumbnail": "https://tse1.mm.bing.net/th?id=OIP.hzniWBxLE_MciorUH3MI4wHaE9&pid=Api",
      "url": "https://www.youm7.com/story/2020/11/23/محمد-رمضان-يشارك-جمهوره-صورة-العلم-الفلسطيني-بعد-أزمته-الأخيرة/5079928",
      "height": 1340,
      "width": 2000,
      "source": "Bing"
    }
  ]
}
```
</details>

### **YouTube Search**:

- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/search/youtube-video?query=فلسطين"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "youtube": [
    {
      "content": "https://www.youtube.com/watch?v=fDjPdz0EWGM",
      "description": "بالزغاريد وقرع الأجراس #shortsvideo #shortvideo #shorts #short تابع البث المباشر لقناة رؤيا الإخبارية ينقل لكم آخر الأخبار المحلية الأردنية وأخبار فلسطين وأبرز الأخبار العربية والدولية https://roya.tv/live-stream/21 http ...",
      "duration": "0:50",
      "embed_html": "<iframe width=\"1280\" height=\"720\" src=\"https://www.youtube.com/embed/fDjPdz0EWGM?autoplay=1\" frameborder=\"0\" allowfullscreen></iframe>",
      "embed_url": "https://www.youtube.com/embed/fDjPdz0EWGM?autoplay=1",
      "image_token": "c204ad97321e5800bf051d73d7728fd48dfe157bf2bdc23cf188af6829ca404c",
      "images": {
        "large": "https://tse4.mm.bing.net/th?id=OVF.hUAXODMtdbyXMaoY%2br1ZXQ&pid=Api",
        "medium": "https://tse4.mm.bing.net/th?id=OVF.hUAXODMtdbyXMaoY%2br1ZXQ&pid=Api",
        "motion": "",
        "small": "https://tse4.mm.bing.net/th?id=OVF.hUAXODMtdbyXMaoY%2br1ZXQ&pid=Api"
      },
      "provider": "Bing",
      "published": "2025-02-19T00:43:10.0000000",
      "publisher": "YouTube",
      "statistics": {
        "viewCount": 1120
      },
      "title": "بالزغاريد وقرع الأجراس #shortsvideo #shortvideo #shorts #short",
      "uploader": "Roya News"
    },
    {
      "content": "https://www.youtube.com/watch?v=RTythF-5shk",
      "description": "القوى الوطنية الفلسطينية في غزة تدعو إلى إنهاء كافة أشكال التطبيع وعقد اجتماع طارئ للفصائل تابعوا أبرز الأخبار، وآخر مستجدات الأحداث العربية والعالمية، عبر البث المباشر للتلفزيون العربي ...",
      "duration": "0:50",
      "embed_html": "<iframe width=\"1280\" height=\"720\" src=\"https://www.youtube.com/embed/RTythF-5shk?autoplay=1\" frameborder=\"0\" allowfullscreen></iframe>",
      "embed_url": "https://www.youtube.com/embed/RTythF-5shk?autoplay=1",
      "image_token": "60f924bfc0344f8fc7125290e9fa3eee6ca7f891e5bbb70bda9f6493c686547e",
      "images": {
        "large": "https://tse4.mm.bing.net/th?id=OVF.tvQemUtk7iI800W8wIIxKw&pid=Api",
        "medium": "https://tse4.mm.bing.net/th?id=OVF.tvQemUtk7iI800W8wIIxKw&pid=Api",
        "motion": "",
        "small": "https://tse4.mm.bing.net/th?id=OVF.tvQemUtk7iI800W8wIIxKw&pid=Api"
      },
      "provider": "Bing",
      "published": "2025-02-19T12:20:58.0000000",
      "publisher": "YouTube",
      "statistics": {
        "viewCount": 2
      },
      "title": "القوى الوطنية الفلسطينية في غزة تدعو إلى إنهاء كافة أشكال التطبيع وعقد اجتماع طارئ للفصائل",
      "uploader": "العربي - أخبار"
    },
    {
      "content": "https://www.youtube.com/watch?v=YMRQ8BaYCOg",
      "description": "يكشف الفيلم عن طبيعة الحياة في فلسطين قبل ما يزيد عن 100 عام، إذ يتتبع مقومات الدولة الفلسطينية في عام 1920 وقبل احتلالها إسرائيلياً بالوقوف على الأدلة والشواهد التي تُثبت وجود دولة مكتملة ...",
      "duration": "50:12",
      "embed_html": "<iframe width=\"1280\" height=\"720\" src=\"https://www.youtube.com/embed/YMRQ8BaYCOg?autoplay=1\" frameborder=\"0\" allowfullscreen></iframe>",
      "embed_url": "https://www.youtube.com/embed/YMRQ8BaYCOg?autoplay=1",
      "image_token": "15a1d6e9731caa321719a538fe90bca8653826d8838a9f2b7a5525a164ab4ccb",
      "images": {
        "large": "https://tse1.mm.bing.net/th?id=OVP.urY9kFPmpa0RCn-e8IC1DgHgFo&pid=Api",
        "medium": "https://tse1.mm.bing.net/th?id=OVP.urY9kFPmpa0RCn-e8IC1DgHgFo&pid=Api",
        "motion": "https://tse3.mm.bing.net/th?id=OM.h6Nh8Qh0K9SFDg_1734717903&pid=Api",
        "small": "https://tse1.mm.bing.net/th?id=OVP.urY9kFPmpa0RCn-e8IC1DgHgFo&pid=Api"
      },
      "provider": "Bing",
      "published": "2021-04-11T19:00:09.0000000",
      "publisher": "YouTube",
      "statistics": {
        "viewCount": 992181
      },
      "title": "فلسطين 1920",
      "uploader": "AlJazeera Arabic قناة الجزيرة"
    }
  ]
}
```
</details>

### **Google News Search**:

- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/search/google-news?query=فلسطين"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "news": [
    {
      "date": "2025-02-19T19:50:00+00:00",
      "title": "عباس رافضا دعوات التهجير: فلسطين ليست للبيع",
      "body": "أكد الرئيس الفلسطيني محمود عباس، أن فلسطين \"ليست للبيع\"، مجددا رفضه دعوات تهجير الشعب الفلسطيني، وجدد التمسك بالشرعية الدولية ومبادرة السلام العربية كأساس لأي حل سياسي للقضية الفلسطينية.",
      "url": "https://www.aljazeera.net/news/2025/2/19/عباس-رافضا-دعوات-التهجير-فلسطين-ليست",
      "image": "https://www.aljazeera.net/wp-content/uploads/2020/05/f8d52c43-fd94-4569-9f58-e0b33772ce90.jpeg?resize=270,180&quality=80",
      "source": "Al Jazeera"
    },
    {
      "date": "2025-02-19T14:22:00+00:00",
      "title": "115 مليون دولار صافي أرباح 38 شركة في بورصة فلسطين والبنوك مؤجلة حتى منتصف آذار",
      "body": "نابلس- معا- استلمت بورصة فلسطين البيانات المالية الختامية الأولية لنتائج أعمال العام 2024 من 38 شركة مدرجة من أصل 48 شركة، وذلك باستثناء البنوك المدرجة، بناء على قرار هيئة سوق رأس المال الفلسطينية الق",
      "url": "https://www.maannews.net/news/2134827.html",
      "image": "https://www.maannews.net/cached_uploads/resize/1200/630/n/2025/02/19/2c53f08c-b30b-40e1-8f86-bfeb516a9d60-1739974789.jpg?_mhk=2fb2608498b3c9376bd523799b5a7ea881d46956f28fc1ea28e4ae85f6f078011c65699fc0c17dcebebea05af7641f03",
      "source": "وكـالـة مـعـا الاخـبـارية"
    },
    {
      "date": "2025-02-19T12:22:00+00:00",
      "title": "قاضى قضاة فلسطين: مصر سد منيع أمام مخططات التهجير",
      "body": "أكد الدكتور محمود الهباش، قاضى قضاة فلسطين ومستشار الرئيس الفلسطينى للشؤون الدينية والعلاقات الإسلامية، أن مصر كانت وما زالت سدًا منيعًا أمام مخططات تهجير الفلسطينيين.",
      "url": "https://www.youm7.com/story/2025/2/19/قاضى-قضاة-فلسطين-مصر-سد-منيع-أمام-مخططات-التهجير/6889466",
      "image": "https://img.youm7.com/large/202106050852575257.jpg",
      "source": "youm7"
    }
  ]
}
```
</details>

### **TikTok Search Video**:

- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/search/tiktok-video?query=قرآن"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "tiktok": [
    {
      "aweme_id": "v14044g50000ctavhs7og65t6151end0",
      "video_id": "7446132611669380368",
      "region": "EG",
      "title": "عٌلَـمًـهّ شُدٍيَـدٍ آلَـقُـوٌيَ 🤍🥺#القارئ #محمود_الشحات_أنور #قران #القران_الكريم #لا_اله_الا_الله #محمد_رسول_الله #ارح_سمعك_بالقران #صلي_علي_النبي_محمد_صلي_الله_عليه_وسلم #سبحان_الله_وبحمده_سبحان_الله_العظيم ",
      "cover": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-p-0037/o0OAoQr1aEkIfAFjnDbQwVqAAqImAUfCHleDE8~tplv-tiktokx-origin.image?biz_tag=musically_video.video_cover&dr=1370&idc=maliva&nonce=25458&ps=933b5bde&refresh_token=468348b6413ca0389333279fa46dbf1b&s=SEARCH&sc=cover&shcp=c1333099&shp=d05b14bd&t=bacd0480&x-expires=1740117600&x-signature=DTLwbvs7CWypCG1y%2BfNi3ekVSc4%3D",
      "ai_dynamic_cover": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-p-0037/o0OAoQr1aEkIfAFjnDbQwVqAAqImAUfCHleDE8~tplv-tiktokx-origin.image?dr=1364&nonce=90734&refresh_token=511ffc9ca4e3213c17f8922060595589&x-expires=1740117600&x-signature=DTLwbvs7CWypCG1y%2BfNi3ekVSc4%3D&biz_tag=tt_video&idc=maliva&ps=4f5296ae&s=SEARCH&sc=cover&shcp=c1333099&shp=d05b14bd&t=bacd0480",
      "origin_cover": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-p-0037/o8QrQADYjeQqAHDOYFCxfuWJ0j6IwEGAoufmC5~tplv-tiktokx-360p.jpeg?dr=1363&nonce=48686&refresh_token=a29d9645d69fa6841e2f357e326ed9c2&x-expires=1740117600&x-signature=mOcAlD%2FZrBQ%2FfQxJukuHYlRSSfU%3D&biz_tag=tt_video&idc=maliva&ps=d97f9a4f&s=SEARCH&sc=cover&shcp=c1333099&shp=d05b14bd&t=bacd0480",
      "duration": 22,
      "play": "https://v39-jp.tiktokcdn.com/06c26ab489fbd7c3e3313061fe8916d7/67b823ae/video/tos/alisg/tos-alisg-pve-0037c001/oI2uIDrEjoJfujS0eAgfjIZqQAYOQ6DHSwmDFC/?a=1233&bti=NEBzNTY6QGo6OjZALnAjNDQuYCMxNDNg&ch=0&cr=0&dr=0&er=0&lr=all&net=0&cd=0%7C0%7C0%7C0&cv=1&br=1216&bt=608&cs=0&ds=6&ft=WcG7iN5TVBzwUiyrTaiG~Be5SphJEBPXtpkU06oyqF_4&mime_type=video_mp4&qs=4&rc=OThnM2VkPDVmOGQ0ZjhnN0BpM3E0NHc5cnZ5dzMzODczNEBhMS9eNC0wNjExNTYtYjZeYSNhYjIzMmQ0ZV5gLS1kMTFzcw%3D%3D&vvpl=1&l=20250220065622E63887403CB5C68E6890&btag=e000bd000",
      "wmplay": "https://v39-jp.tiktokcdn.com/e9d228749414f4476b93172386baa43a/67b823ae/video/tos/alisg/tos-alisg-pve-0037c001/owurwYjEjJjQgI7QuCFOAeaDA0o8GDXmffqIu6/?a=1233&bti=NEBzNTY6QGo6OjZALnAjNDQuYCMxNDNg&ch=0&cr=0&dr=0&er=0&lr=all&net=0&cd=0%7C0%7C0%7C0&cv=1&br=2346&bt=1173&cs=0&ds=3&ft=WcG7iN5TVBzwUiyrTaiG~Be5SphJEBPXtpkU06oyqF_4&mime_type=video_mp4&qs=0&rc=MzozODdlOTNpOWRpOzhmO0BpM3E0NHc5cnZ5dzMzODczNEBiXzExLl8xNjAxNTQtLWAvYSNhYjIzMmQ0ZV5gLS1kMTFzcw%3D%3D&vvpl=1&l=20250220065622E63887403CB5C68E6890&btag=e000bd000",
      "size": 1780231,
      "wm_size": 3436005,
      "music": "https://sf16-ies-music-sg.tiktokcdn.com/obj/tiktok-obj/7446132840648952593.mp3",
      "music_info": {
        "id": "7446132854822341392",
        "title": "original sound - .m1670",
        "play": "https://sf16-ies-music-sg.tiktokcdn.com/obj/tiktok-obj/7446132840648952593.mp3",
        "cover": "https://p16-sg.tiktokcdn.com/tos-alisg-avt-0068/f790a0c6ac7d36ae699401cc191d805b~tplv-tiktokx-cropcenter-q:1080:1080:q80.jpeg?dr=10796&idc=maliva&nonce=34191&ps=87d6e48a&refresh_token=e14357da40abc516e8cdf2deb2aac346&s=SEARCH&sc=avatar&shcp=c1333099&shp=45126217&t=223449c4",
        "author": "التائبون 🥺🤍🤲🏻",
        "original": true,
        "duration": 22,
        "album": ""
      },
      "play_count": 1484850,
      "digg_count": 106963,
      "comment_count": 864,
      "share_count": 3493,
      "download_count": 32799,
      "create_time": 1733687903,
      "anchors": null,
      "anchors_extras": "",
      "is_ad": false,
      "commerce_info": {
        "auction_ad_invited": false,
        "with_comment_filter_words": false,
        "adv_promotable": false,
        "branded_content_type": 0
      },
      "commercial_video_info": "",
      "item_comment_settings": 0,
      "mentioned_users": "",
      "author": {
        "id": "7276821626619560965",
        "unique_id": ".m1670",
        "nickname": "التائبون 🥺🤍🤲🏻",
        "avatar": "https://p16-sg.tiktokcdn.com/tos-alisg-avt-0068/f790a0c6ac7d36ae699401cc191d805b~tplv-tiktokx-cropcenter-q:300:300:q75.jpeg?dr=10793&idc=maliva&nonce=71164&ps=87d6e48a&refresh_token=085f30f765f720230c1f478cf3887afb&s=SEARCH&sc=avatar&shcp=c1333099&shp=45126217&t=223449c4"
      },
      "is_top": 0
    },
    {
      "aweme_id": "v1c044g50000crspchfog65haf8ml340",
      "video_id": "7420127304766065927",
      "region": "TR",
      "title": "#CapCut #قران #قران_كريم #قران_كريم_ارح_سمعك_وقلبك #تلاوة #تلاوة_خاشعة #تلاوة_خاشعة_تريح_القلب_والعقل🎧😴 #quran_alkarim #quran #اكسبلور #viral #fyp #اكتب_شي_توجر_عليه ",
      "cover": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-p-0037/osFiIIcRgEEMUPBqBdgijfoSEflFmiiB9Esx5A~tplv-tiktokx-origin.image?biz_tag=musically_video.video_cover&dr=1370&idc=maliva&nonce=19789&ps=933b5bde&refresh_token=485632b506a158a335b40ea92c370ed3&s=SEARCH&sc=cover&shcp=c1333099&shp=d05b14bd&t=bacd0480&x-expires=1740117600&x-signature=Wwl8ow%2Fj85YLu9dqaGZADlB8tqk%3D",
      "ai_dynamic_cover": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-p-0037/1552917b72cc49f99337642427ebeec2_1727633028~tplv-tiktokx-origin.image?dr=1364&nonce=51511&refresh_token=5618f2da4789117578c6b734e46c4329&x-expires=1740117600&x-signature=KCbgkZp4PtvoZEEhiWhGGIrgywU%3D&biz_tag=tt_video&idc=maliva&ps=4f5296ae&s=SEARCH&sc=cover&shcp=c1333099&shp=d05b14bd&t=bacd0480",
      "origin_cover": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-p-0037/886fc26243f247f5a7f28eab7c577fe9_1727633027~tplv-tiktokx-360p.jpeg?dr=1363&nonce=6894&refresh_token=52ce90309cee903996c6e3a4422c05be&x-expires=1740117600&x-signature=2AO%2BX%2BI6dIXuBmKywukKlEOnzuI%3D&biz_tag=tt_video&idc=maliva&ps=d97f9a4f&s=SEARCH&sc=cover&shcp=c1333099&shp=d05b14bd&t=bacd0480",
      "duration": 13,
      "play": "https://v39-jp.tiktokcdn.com/852926eb850970795edbb40b9c6e9d53/67b823a5/video/tos/alisg/tos-alisg-pve-0037c001/ooQZKg4DNCLiGdVFECSZNAQpIDLzfeeA6jIQnF/?a=1233&bti=NTY6QGo0QHM6OjZANDQuYCMucCMxNDNg&ch=0&cr=0&dr=0&er=0&lr=all&net=0&cd=0%7C0%7C0%7C0&cv=1&br=1362&bt=681&cs=0&ds=6&ft=WcG7iN5TVBzwUiyrTaiG~Be5SphJEBPXtpkU06oyqF_4&mime_type=video_mp4&qs=0&rc=NjdnM2g7aWRmOGc6ODk1PEBpMzZwaWs5cmtzdTMzODczNEA1MS1hYjNjXjIxX2FhYTVeYSMxaTVeMmRjYHBgLS1kMWBzcw%3D%3D&vvpl=1&l=20250220065622E63887403CB5C68E6890&btag=e000b5000",
      "wmplay": "https://v39-jp.tiktokcdn.com/6fa4731deedd35afb91f1327e35cf80f/67b823a5/video/tos/alisg/tos-alisg-pve-0037c001/oUgBqiMFmBLgljixABBdTzmfiQsIcEfRoE9U5I/?a=1233&bti=NTY6QGo0QHM6OjZANDQuYCMucCMxNDNg&ch=0&cr=0&dr=0&er=0&lr=all&net=0&cd=0%7C0%7C0%7C0&cv=1&br=1400&bt=700&cs=0&ds=3&ft=WcG7iN5TVBzwUiyrTaiG~Be5SphJEBPXtpkU06oyqF_4&mime_type=video_mp4&qs=0&rc=O2Q3PDQ7NjRlNWYzNjZpN0BpMzZwaWs5cmtzdTMzODczNEBiYy82XjUxNjExMS80L18wYSMxaTVeMmRjYHBgLS1kMWBzcw%3D%3D&vvpl=1&l=20250220065622E63887403CB5C68E6890&btag=e000b5000",
      "size": 1201139,
      "wm_size": 1233911,
      "music": "https://sf16-ies-music-sg.tiktokcdn.com/obj/tiktok-obj/7396686039925099282.mp3",
      "music_info": {
        "id": "7396679892753500945",
        "title": "original sound - kh.hashmi1",
        "play": "https://sf16-ies-music-sg.tiktokcdn.com/obj/tiktok-obj/7396686039925099282.mp3",
        "cover": "https://p16-sg.tiktokcdn.com/tos-alisg-avt-0068/d2f4bd116044e6ed720921ddf0879e94~tplv-tiktokx-cropcenter-q:1080:1080:q80.jpeg?dr=10796&idc=maliva&nonce=93258&ps=87d6e48a&refresh_token=9801f40215c6c2548e00005207a1025d&s=SEARCH&sc=avatar&shcp=c1333099&shp=45126217&t=223449c4",
        "author": "❤kh.hashmi❤",
        "original": true,
        "duration": 13,
        "album": ""
      },
      "play_count": 1141365,
      "digg_count": 47694,
      "comment_count": 495,
      "share_count": 4770,
      "download_count": 34688,
      "create_time": 1727633024,
      "anchors": null,
      "anchors_extras": "",
      "is_ad": false,
      "commerce_info": {
        "auction_ad_invited": false,
        "with_comment_filter_words": false,
        "adv_promotable": false,
        "branded_content_type": 0
      },
      "commercial_video_info": "",
      "item_comment_settings": 0,
      "mentioned_users": "",
      "author": {
        "id": "7150771695594783750",
        "unique_id": "user638557218quran",
        "nickname": "قرآن كريم",
        "avatar": "https://p16-amd-va.tiktokcdn.com/tos-maliva-avt-0068/c94b7a680f44205e4ea68ffcaf7fe789~tplv-tiktokx-cropcenter-q:300:300:q75.jpeg?dr=10793&idc=maliva&nonce=91885&ps=87d6e48a&refresh_token=c605ef4459830d37eebdbcdc40e9a47a&s=SEARCH&sc=avatar&shcp=c1333099&shp=45126217&t=223449c4"
      },
      "is_top": 0
    },
    {
      "aweme_id": "v14044g50000crb1tqnog65t9ccd4dvg",
      "video_id": "7410144912013823250",
      "region": "EG",
      "title": "#خالد_الجليل #ارح_سمعك_بالقران #قران #راحة_نفسية #تلاوة_خاشعة #islamic_video #quran #allahuakbar #muslim #mashallah #muslimtiktok #اكسبلورexplore #allah ",
      "cover": "https://p16-sign-sg.tiktokcdn.com/obj/tos-alisg-p-0037/edb13ffa7aba43d7a55f9ba45e99c86a?biz_tag=musically_video.video_cover&lk3s=c1333099&nonce=28218&refresh_token=94e40ca89838879830d5d812ec0d2fc7&shcp=-&shp=c1333099&x-expires=1740052800&x-signature=yukEsEEKNfSnhq7hCvfAyRpoJK8%3D",
      "ai_dynamic_cover": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-p-0037/48e17970e4724376bc0d77cbdd27f9bb_1725308825~tplv-tiktokx-origin.image?dr=1364&nonce=23798&refresh_token=56b0aff328244f4373d12234b631b988&x-expires=1740117600&x-signature=rz0VfjKnPBVg68JvK4XOaChAPZE%3D&biz_tag=tt_video&idc=maliva&ps=4f5296ae&s=SEARCH&sc=cover&shcp=c1333099&shp=d05b14bd&t=bacd0480",
      "origin_cover": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-p-0037/ac8d318c16934a9e8a92bcb5dacfbac0_1725308825~tplv-tiktokx-360p.jpeg?dr=1363&nonce=65892&refresh_token=7219d1dbeca24336c5bca4b4af9f7c1b&x-expires=1740117600&x-signature=W45WUpQG1Vnt94s2KhhXI%2FWSNrY%3D&biz_tag=tt_video&idc=maliva&ps=d97f9a4f&s=SEARCH&sc=cover&shcp=c1333099&shp=d05b14bd&t=bacd0480",
      "duration": 14,
      "play": "https://v39-jp.tiktokcdn.com/647235beed84689feda06b8992ffd598/67b823a6/video/tos/alisg/tos-alisg-pve-0037c001/oMoCrKGAfDNGPL1pYW0j5Ve3I3DLWHINAQeIIv/?a=1233&bti=NTY6QGo0QHM6OjZANDQuYCMucCMxNDNg&ch=0&cr=0&dr=0&er=0&lr=all&net=0&cd=0%7C0%7C0%7C0&cv=1&br=858&bt=429&cs=0&ds=6&ft=WcG7iN5TVBzwUiyrTaiG~Be5SphJEBPXtpkU06oyqF_4&mime_type=video_mp4&qs=4&rc=M2Y0OWRpaDUzZDg2ZjZkNUBpamdnZnc5cnQ0dTMzODczNEAyMV4uM2MwXmIxMzNeNGI0YSNzMWA2MmRrcV9gLS1kMTFzcw%3D%3D&vvpl=1&l=20250220065622E63887403CB5C68E6890&btag=e000bd000",
      "wmplay": "https://v39-jp.tiktokcdn.com/044246f54c1cc0b602fa744ced864a7d/67b823a6/video/tos/alisg/tos-alisg-pve-0037c001/oQDlW5f7QGbhmFBExl6BAqUfE1EBHIjgRkjb10/?a=1233&bti=NTY6QGo0QHM6OjZANDQuYCMucCMxNDNg&ch=0&cr=0&dr=0&er=0&lr=all&net=0&cd=0%7C0%7C0%7C0&cv=1&br=1614&bt=807&cs=0&ds=3&ft=WcG7iN5TVBzwUiyrTaiG~Be5SphJEBPXtpkU06oyqF_4&mime_type=video_mp4&qs=0&rc=NTU7aGdoNDc0NWU2Nmc3NEBpamdnZnc5cnQ0dTMzODczNEBjLTFiNS8tNjUxLjUwYjUuYSNzMWA2MmRrcV9gLS1kMTFzcw%3D%3D&vvpl=1&l=20250220065622E63887403CB5C68E6890&btag=e000bd000",
      "size": 798119,
      "wm_size": 1499841,
      "music": "https://sf16-ies-music-sg.tiktokcdn.com/obj/tiktok-obj/7410144961876134673.mp3",
      "music_info": {
        "id": "7410144973351406353",
        "title": "original sound - master.mutasim",
        "play": "https://sf16-ies-music-sg.tiktokcdn.com/obj/tiktok-obj/7410144961876134673.mp3",
        "cover": "https://p16-amd-va.tiktokcdn.com/tos-maliva-avt-0068/b796ff5616e52c62d2de7368002c531b~tplv-tiktokx-cropcenter-q:1080:1080:q75.jpeg?dr=10796&idc=maliva&nonce=64080&ps=87d6e48a&refresh_token=4d1430f528c5f550082b72305487d9f7&s=SEARCH&sc=avatar&shcp=c1333099&shp=45126217&t=223449c4",
        "author": "muslim مسلم",
        "original": true,
        "duration": 14,
        "album": ""
      },
      "play_count": 5687822,
      "digg_count": 100391,
      "comment_count": 13056,
      "share_count": 3584,
      "download_count": 11435,
      "create_time": 1725308823,
      "anchors": null,
      "anchors_extras": "",
      "is_ad": false,
      "commerce_info": {
        "auction_ad_invited": false,
        "with_comment_filter_words": false,
        "adv_promotable": false,
        "branded_content_type": 0
      },
      "commercial_video_info": "",
      "item_comment_settings": 0,
      "mentioned_users": "",
      "author": {
        "id": "7348811581759276037",
        "unique_id": "master.mutasim",
        "nickname": "muslim مسلم",
        "avatar": "https://p16-amd-va.tiktokcdn.com/tos-maliva-avt-0068/b796ff5616e52c62d2de7368002c531b~tplv-tiktokx-cropcenter-q:300:300:q75.jpeg?dr=10793&idc=maliva&nonce=72509&ps=87d6e48a&refresh_token=8c7ac3180d394596440540f0dfd5921b&s=SEARCH&sc=avatar&shcp=c1333099&shp=45126217&t=223449c4"
      },
      "is_top": 0
    }
  ]
}
```
</details>

### **Monica Search Ai**:

- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/search/monica-search?query=شركة+ميتا"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "data": [
    {
      "text": "تُعتبر شركة **ميتا بلاتفورمز** (Meta Platforms, Inc.)، المعروفة سابقًا باسم فيسبوك، واحدة من أبرز الشركات في مجال التكنولوجيا ووسائل التواصل الاجتماعي. تأسست الشركة عام2004 على يد مارك زوكربيرغ وعدد من زملائه من جامعة هارفارد، ومنذ ذلك الحين نمت لتصبح قوة رائدة في عالم الاتصال الرقمي. يقع مقرها الرئيسي في مينلو بارك، كاليفورنيا، وتدير عددًا من المنصات الشهيرة مثل فيسبوك، وإنستغرام، وواتساب، وThreads، والتي تُستخدم من قبل العديد من المستخدمين حول العالم [1,5].\n\nفي أكتوبر2021، أعلنت شركة فيسبوك عن تغيير اسمها إلى \"ميتا\" كجزء من تحولها نحو بناء الميتافيرس، وهو مفهوم يهدف إلى توفير بيئة تواصل أكثر تفاعلية وغامرة. يعكس هذا الانتقال رغبة الشركة في الابتكار والاستثمار في التقنيات الجديدة مثل الواقع الافتراضي والمعزز [2,15].\n\nتعتبر الإعلانات المصدر الرئيسي للإيرادات في شركة ميتا، حيث تُعرف الشركة بأنها واحدة من أكبر شركات الإعلان في العالم، إذ يُشكل الإعلان حوالي97.8% من إيراداتها [5].ومع ذلك، واجهت ميتا تحديات كبيرة، خاصةً بعد انخفاض قيمة أسهمها بشكل ملحوظ، مما أثار مخاوف حول استراتيجيتها في المستقبل وما إذا كانت استثماراتها في الميتافيرس ستؤتي ثمارها أو ستؤدي إلى مزيد من المشكلات المالية [10].تسعى الشركة حاليًا إلى تحسين تجربتها للمستخدمين وتوسيع نطاقها من خلال تطوير تقنيات متقدمة وابتكارات جديدة في مجال الذكاء الاصطناعي والواقع الافتراضي، لضمان استمرار ريادتها في السوق [3,14].",
      "search_result": [
        {
          "id": 1,
          "name": "ميتا بلاتفورمز - ويكيبيديا",
          "url": "https://ar.wikipedia.org/wiki/%D9%85%D9%8A%D8%AA%D8%A7_%D8%A8%D9%84%D8%A7%D8%AA%D9%81%D9%88%D8%B1%D9%85%D8%B2",
          "display_url": "https://ar.wikipedia.org/wiki/%D9%85%D9%8A%D8%AA%D8%A7_%D8%A8%D9%84%D8%A7%D8%AA%D9%81%D9%88%D8%B1%D9%85%D8%B2",
          "snippet": "شركة ميتا بلاتفورمز (بالإنجليزية: .Meta Platforms, Inc)، تمارس النشاط التجاري باسم ميتا (Meta) والمعروفة سابقًا باسم شركة فيسبوك (.Facebook, Inc) هي شركة ...",
          "language": "",
          "thumbnail_url": "",
          "website_name": "wikipedia.org"
        },
        {
          "id": 2,
          "name": "Meta | Social Metaverse Company",
          "url": "https://about.meta.com/",
          "display_url": "https://about.meta.com/",
          "snippet": "Meta (formerly the Facebook company) builds the future of human connection and the technology that makes it possible. We're moving beyond 2D screens and ...",
          "language": "",
          "thumbnail_url": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTGKcWFyvcm_WJ_eBEgwrExyEndCWnuMQIblXHz9D3Pjn5A7vSxRmrAX7Ym&s",
          "website_name": "meta.com"
        },
        {
          "id": 16,
          "name": "Meta Materials Inc. - Functional Materials and Nanocomposites",
          "url": "https://metamaterial.com/",
          "display_url": "https://metamaterial.com/",
          "snippet": "META (NASDAQ: MMAT) was an advanced materials and nanotechnology company (2010-2024). We develop new products and technologies using innovative sustainable ...",
          "language": "",
          "thumbnail_url": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTla52igVpNLiTQ_A6LAYEW38WHQvhqbXdLBRXgyx6eC7JiamFOijYExNP_&s",
          "website_name": "metamaterial.com"
        }
      ]
    }
  ]
}
```
</details>

## **5. Games ⬇️**
### **Info Player FreeFire**:

- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/games/info-player-ff?id=688851460"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "freefire": [
    {
      "basicInfo": {
        "accountId": "688851460",
        "accountType": 1,
        "nickname": "كنـترول『ᵒ²』",
        "region": "ME",
        "level": 60,
        "exp": 1015708,
        "bannerId": 901000102,
        "headPic": 902000105,
        "rank": 201,
        "rankingPoints": 1000,
        "badgeId": 1001000081,
        "seasonId": 43,
        "liked": 2704,
        "isDeleted": true,
        "lastLoginAt": "1605389272",
        "csRank": 201,
        "weaponSkinShows": [
          907192402
        ],
        "maxRank": 201,
        "csMaxRank": 201,
        "accountPrefers": [],
        "createAt": "1548772238",
        "externalIconInfo": {
          "status": "ExternalIconStatus_NOT_IN_USE",
          "showType": "ExternalIconShowType_FRIEND"
        },
        "avatars": [
          "https://cdn.neferbyte.com/api/v1/ff/avatar/png?image=5CjmE2YlNC801vO1513T8lQ3emVYeGdHK3FNd0xQTWpUdG41TGVxSzlpVExReWxZKzk4NElYTTRlVVQ0NzFjTlE5Mko3cE5HZGl3ME51REtiQzJzd1pzaWUyTGFzSXhFdGZKMnltUXdvNHo3b3BBTWt6eXRsUlMydmJteVpCOUVJeGRjTXRVNVBTUHFEM1F3UWtPc1JXNitCRlF2aXFhZVE4aU9LbGI1V2s5RXdlbkZRVE5kclY4WVdYMnNHcVFrME9meTRHN3RCRjRVd0krVDh3TTlaZ2l6WFhSWkdvLzJwVGhrNEo0WHdFeEt4V2czK0VQMU9RZHc1RW9DSGxBT2lQSmpSRGlRdXZLME53VGE%3D",
          "https://cdn.neferbyte.com/api/v1/ff/avatar/webp?image=5CjmE2YlNC801vO1513T8lQ3emVYeGdHK3FNd0xQTWpUdG41TGVxSzlpVExReWxZKzk4NElYTTRlVVQ0NzFjTlE5Mko3cE5HZGl3ME51REtiQzJzd1pzaWUyTGFzSXhFdGZKMnltUXdvNHo3b3BBTWt6eXRsUlMydmJteVpCOUVJeGRjTXRVNVBTUHFEM1F3UWtPc1JXNitCRlF2aXFhZVE4aU9LbGI1V2s5RXdlbkZRVE5kclY4WVdYMnNHcVFrME9meTRHN3RCRjRVd0krVDh3TTlaZ2l6WFhSWkdvLzJwVGhrNEo0WHdFeEt4V2czK0VQMU9RZHc1RW9DSGxBT2lQSmpSRGlRdXZLME53VGE%3D"
        ]
      },
      "profileInfo": {
        "avatarId": 102000015,
        "clothes": {
          "ids": [
            "203000872",
            "204000055",
            "205000051",
            "214000000",
            "211000168",
            "211000058"
          ],
          "images": [
            "https://cdn.neferbyte.com/api/v1/ff/clothes/png?image=5CjmE2YlNC801vO1513T8lROMzBickFOdm9iY0UyTzNpTnMvS0tYUVg4Nnk2RURXT0czRTNsL3RxRGRLdHFlQzQzUXFHN0RGZUE5K291cldQc3E2MDBxS2hSNGM2ZmgvSWVuc0R4QTh2d21JQzEzbzg3Q2ZWY2lHa1BvQ3VqemJDUGtwUkN1VWlvS1d6cWtpT0lZaHl4dGZFeElaY3pHWWhZQlJrZG5QeXJtU1VZblBXb1hsYzV0eTd5MVA3dDlQY3BTV253M2RMQnJQWmlyQkllVGdOQzcyamtSWHdFdndyS1RUekE9PQ%3D%3D",
            "https://cdn.neferbyte.com/api/v1/ff/clothes/webp?image=5CjmE2YlNC801vO1513T8lROMzBickFOdm9iY0UyTzNpTnMvS0tYUVg4Nnk2RURXT0czRTNsL3RxRGRLdHFlQzQzUXFHN0RGZUE5K291cldQc3E2MDBxS2hSNGM2ZmgvSWVuc0R4QTh2d21JQzEzbzg3Q2ZWY2lHa1BvQ3VqemJDUGtwUkN1VWlvS1d6cWtpT0lZaHl4dGZFeElaY3pHWWhZQlJrZG5QeXJtU1VZblBXb1hsYzV0eTd5MVA3dDlQY3BTV253M2RMQnJQWmlyQkllVGdOQzcyamtSWHdFdndyS1RUekE9PQ%3D%3D"
          ]
        },
        "equippedSkills": [
          {
            "skillId": 2206
          },
          {
            "slotId": 1,
            "skillId": 705
          },
          {
            "slotId": 2,
            "skillId": 2006
          },
          {
            "slotId": 3,
            "skillId": 206
          }
        ],
        "isSelected": true,
        "isSelectedAwaken": true
      },
      "clanBasicInfo": [],
      "petInfo": [],
      "socialInfo": [],
      "diamondCostRes": {
        "diamondCost": 390
      },
      "creditScoreInfo": {
        "periodicSummaryEndTime": "259200"
      }
    }
  ]
}
```
</details>

### **Info Player Brawl Stars**:

- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/games/info-brawl-stars?id=YP0VYR9JG"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "brawlstars": [
    {
      "rank": "https://brawlbot.xyz/api/image/rank/YP0VYR9JG",
      "mastery": "https://brawlbot.xyz/api/image/mastery/YP0VYR9JG"
    }
  ]
}
```
</details>

## **6. Islamic ⬇️**
### **Prayer Times Oman**:

- **Example Request:**
```bash
curl -X GET "https://api-streamline-pro.vercel.app/api/islamic/prayer-times-om?city=مسقط"
```
<details> <summary>🔽 JSON Response</summary>

```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "prayertimes": [
    {
      "city": "مسقط",
      "gregoriandate": "Thursday 20 February 2025 CE  21 Sha'ban 1446 AH",
      "hijridate": "الخميس 20 فبراير 2025 ميلادى  21 شعبان 1446 هجرى",
      "prayertimes": {
        "تاريخ": "20/2/2025",
        "الفجر": "05:20",
        "الشروق": "06:36",
        "الظهر": "12:26",
        "العصر": "03:43",
        "المغرب": "06:10",
        "العشاء": "07:21"
      }
    }
  ]
}
```
</details>


## Credits ⚖️

💡 **Author:** dark man 🔥😎.  
© 2025 dark man. All rights reserved.  

> **Note:** If you use this API in your projects, please provide proper attribution.
