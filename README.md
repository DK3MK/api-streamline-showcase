# API Streamline Showcase

## 📌 Overview
Welcome to **API Streamline Showcase**, a collection of APIs across various categories. Each API offers one of the following three output types:

- 📜 **JSON Data** - Structured and easy-to-use information.
- 🖼️ **Direct Image Output** - Return images directly.
- 🔊 **Live Audio Streams** - Provide direct audio output.

---

## 📂 API Categories & Outputs

### 🔹 1. AI (28 APIs)
- Advanced AI models for text, images, and more.
- **Example Endpoint:** `/api/ai/text-generator`

#### ➤ API Examples:

**ChatGPT**  
- **Endpoint:**  
  `https://api-streamline-pro.vercel.app/api/ai/chatgpt?prompt=hi&userid=123`  
- **Response:**
```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "chatgpt": "Hello! How can I assist you today?"
}
```

**Llama Flare**
- **Endpoint:**  
  `https://api-streamline-pro.vercel.app/api/ai/llama-flare?prompt=hi&system=Virtual+Assistant`
- **Response:**
```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "llama": "Hi! It's nice to meet you. Is there something I can help you with or would you like to chat?"
}
```

**Speech2Text**
- **Endpoint:**  
  `https://api-streamline-pro.vercel.app/api/ai/speech2text?url=https://github.com/DK3MK/worker-bot/raw/refs/heads/main/mp3/test-myapi.wav`
- **Response:**
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

**DeepAI Text2Img**
- **Endpoint:**  
  `https://api-streamline-pro.vercel.app/api/ai/deepai-text2img?text=cyberpunk+cat`
- **Output:** *Direct Image Output.*

**Text2Art**
- **Endpoint:**  
  `https://api-streamline-pro.vercel.app/api/ai/text2art?text=Anime`
- **Response:**
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

**Google Gemma**
- **Endpoint:**  
  `https://api-streamline-pro.vercel.app/api/ai/google-gemma?prompt=hi`
- **Response:**
```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "gemma": "Hi! 👋 It's great to hear from you. How can I help you today? 😊"
}
```

**Chat Chars**
- **Endpoint:**  
  `https://api-streamline-pro.vercel.app/api/ai/chat-chars?prompt=hi&userid=123&char=Play+as+Elon+Musk+to+answer`
- **Response:**
```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "char": "Hello! How can I help you today?"
}
```

- **Direct Image Outputs:**  

**Picasso Pharaonic:**  
  `https://api-streamline-pro.vercel.app/api/ai/picasso-pharaonic?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg`

**Picasso Professional:**  
  `https://api-streamline-pro.vercel.app/api/ai/picasso-professional?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg`

**Picasso Warrior:**  
  `https://api-streamline-pro.vercel.app/api/ai/picasso-warrior?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg`

**Picasso Cyborg:**  
  `https://api-streamline-pro.vercel.app/api/ai/picasso-cyborg?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg`

**Picasso Abstract:**  
  `https://api-streamline-pro.vercel.app/api/ai/picasso-abstract?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg`

**Picasso Oilpainting:**  
  `https://api-streamline-pro.vercel.app/api/ai/picasso-oilpainting?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg`

**Picasso Palestinian:**  
  `https://api-streamline-pro.vercel.app/api/ai/picasso-palestinian?url=https://i.pinimg.com/736x/50/71/f9/5071f99b44b6d75f119f77a54826ef61.jpg`


### 🔹 2. Tools (6 APIs)

**Google Translate**
- **Endpoint:**  
  `https://api-streamline-pro.vercel.app/api/tools/google-translate?text=Hello!&to=ar`
- **Response:**
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

### 🔹 3. Downloader (6 APIs)

**Download TikTok**  
- **Endpoint:**  
  `https://api-streamline-pro.vercel.app/api/downloader/tiktok?url=https://vt.tiktok.com/ZS2tqxmeX/`
- **Response:**
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
### 🔹 4. Games (2 APIs)

**Info Player FreeFire**  
- **Endpoint:**  
  `https://api-streamline-pro.vercel.app/api/games/info-player-ff?id=688851460`
- **Response:**
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
### 🔹 5. Islamic (1 API)

**Prayer Times Oman**  
- **Endpoint:**  
  `https://api-streamline-pro.vercel.app/api/islamic/prayer-times-om?city=مسقط`
- **Response:**
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
### 🔹 6. Search (12 APIs)

**Search YouTube**  
- **Endpoint:**  
 `https://api-streamline-pro.vercel.app/api/search/youtube-video?query=فلسطين`
- **Response:**
```json
{
  "developer": "dark man 👾",
  "status": "success ✅",
  "message": "Data fetched successfully! 🎉",
  "youtube": [
    {
      "content": "https://www.youtube.com/watch?v=DYWrT02ZJDk",
      "description": "حملت ناشطة بريطانية خريطة فلسطين التاريخية تظهر بها مدنها وما تشتهر به كل مدينة من معالم بنيانية أو جغرافية أو زراعية أو مناخية، ومفتاح العودة خلال مظاهرة أمام السفارة الأمريكية بلندن ووثق ...",
      "duration": "1:55",
      "embed_html": "<iframe width=\"1280\" height=\"720\" src=\"https://www.youtube.com/embed/DYWrT02ZJDk?autoplay=1\" frameborder=\"0\" allowfullscreen></iframe>",
      "embed_url": "https://www.youtube.com/embed/DYWrT02ZJDk?autoplay=1",
      "image_token": "d973827a539061c01c9c930f855170a1996a54b4fb4fd6f1f45d89d9a101cdd5",
      "images": {
        "large": "https://tse2.mm.bing.net/th?id=OVF.UCrse4evvwRRr%2foqbGXkvA&pid=Api",
        "medium": "https://tse2.mm.bing.net/th?id=OVF.UCrse4evvwRRr%2foqbGXkvA&pid=Api",
        "motion": "",
        "small": "https://tse2.mm.bing.net/th?id=OVF.UCrse4evvwRRr%2foqbGXkvA&pid=Api"
      },
      "provider": "Bing",
      "published": "2025-02-19T04:40:00.0000000",
      "publisher": "YouTube",
      "statistics": {
        "viewCount": 11068
      },
      "title": "ناشطة تحمل خريطة فلسطين التاريخية ومفتاح العودة خلال مظاهرة بلندن",
      "uploader": "AlJazeera Arabic قناة الجزيرة"
    }
  ]
}
```

- **🚀 Installation & Usage**
```bash
git clone https://github.com/yourusername/api-streamline-showcase.git
cd api-streamline-showcase
npm install  # If needed
```

- **🤝 Contributing**  
  *Feel free to contribute by adding API examples or improving documentation!*

