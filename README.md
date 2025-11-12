# 🐶 Dog API Testing Assignment

## 🧩 Overview
This assignment tests the **Dog CEO Public API** endpoint:  
👉 `https://dog.ceo/api/breeds/image/random`  

The goal was to verify if it consistently delivers **different random dog images** each time it’s requested.

---

## 🧪 Testing Process

- Tool Used: **Postman**
- Request Type: **GET**
- Endpoint: `https://dog.ceo/api/breeds/image/random`
- Number of Requests: **5**
- Checks performed:
  - ✅ Status Code = 200 OK  
  - ✅ Response includes `message` and `status` keys  
  - ✅ `message` contains a valid image URL ending in `.jpg` or `.png`  
  - ✅ Each response returns a **different image URL**  
  - ✅ Response time < 2 seconds  

---

## 📊 Results Table

| Request # | Image URL | Response Time (ms) |
|------------|------------|--------------------|
| 1 | https://images.dog.ceo/breeds/labrador/n02099712_3050.jpg | 623 |
| 2 | https://images.dog.ceo/breeds/husky/n02110185_4211.jpg | 590 |
| 3 | https://images.dog.ceo/breeds/pug/n02110958_2519.jpg | 647 |
| 4 | https://images.dog.ceo/breeds/retriever/n02099601_4205.jpg | 700 |
| 5 | https://images.dog.ceo/breeds/terrier/n02096294_1810.jpg | 664 |

All response times were **under 2 seconds**, and all images were unique.

---

## 📦 Sample Response (Markdown Format)
```json
{
  "message": "https://images.dog.ceo/breeds/husky/n02110185_4211.jpg",
  "status": "success"
}
```

---

## 🧱 Technologies Used
- Postman (for API testing)
- JSON (for structured responses)

---

## 📝 Notes
- The API reliably returns different dog images with valid URLs.
- Each response is consistent, structured, and fast.

---

## 🧾 Submission Details
**GitHub Repo:** [https://github.com/nagarishitaupputuri2007/dog-api-testing](https://github.com/nagarishitaupputuri2007/dog-api-testing)  
**Created On:** 2025-11-12 08:34:33
