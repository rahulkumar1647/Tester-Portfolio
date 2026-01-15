# SIMS API Testing (Postman) - Sample

## 1) Login API
- **Method:** POST
- **Endpoint:** /api/login

### Validations
✅ Status code should be 200  
✅ Response time should be acceptable  
✅ Response should contain token  
✅ Invalid credentials should return proper error message  

---

## 2) Get Student List API
- **Method:** GET
- **Endpoint:** /api/students

### Validations
✅ Status code 200  
✅ Response should return list of students  
✅ Verify mandatory fields exist (id, name, class, mobile)  
✅ Unauthorized request should return 401/403  

---

## 3) Create Student API
- **Method:** POST
- **Endpoint:** /api/students

### Validations
✅ Student should create successfully  
✅ Verify correct data in response  
✅ Missing required fields should return validation error  
