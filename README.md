# POS Malaysia Rate Calculator API Test Collection

This Postman collection tests key APIs related to the [POS Malaysia Rate Calculator](https://pos.com.my/send/ratecalculator).  

The collection includes:  
- Fetching country list  
- Looking up state/district by postcode  
- Calculating shipping quote

---

## 📌 **Collection Overview**
| Request | Purpose |
|----------|---------|
| `Get Country List` | Retrieves available destination countries for shipping |
| `Postcode Lookup` | Returns state and district based on entered postcode |
| `Shipping Quote Calculator` | Calculates shipment cost based on input |

---

## ⚡ **How to Use**
1️⃣ Import the collection into Postman (from the JSON file in this repo).  
2️⃣ Optionally import the environment file (if provided) or set variables manually.  
3️⃣ Run requests individually

## ✅ **Tests Included**
Each request includes basic validations:
- HTTP status code 200
- Expected keys exist in the response
