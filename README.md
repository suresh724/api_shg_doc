## Members Add

```


{
    "members": [
        {
            "member_name": "Ajay",
            "middle_name": "Vijay",
            "email": "ajay@mail.com",
            "contact_number": "1234",
            "village":"kjdk",
            "local_body":"232",
            "block":"2323",
            "district": "23",
            "state": "23",
            "zip_code": "2134",
            "gender": "male",
            "dob": "2022-12-23",
            "social_category": "1",
            "skills": ["html","css"],
            "experience": "Carpentar",
            "experience_year": "3",
            "shg_role": "1",
            "shg_id": "12",
            "pip_category": "POOR",
            "disability": 0,
            "religion": "2",
            "apl": 1
        },
        {
            "member_name": "Vijay",
            "middle_name": "Ajay",
            "email": "vijay@mail.com",
            "contact_number": "1234",
             "village":"kjdk",
            "local_body":"232",
            "block":"2323",
            "district": "23",
            "state": "23",
            "zip_code": "2134",
            "gender": "male",
            "dob": "2022-12-23",
            "social_category": "1",
            "skills": ["html","css","js"],
            "experience": "Carpentar",
            "experience_year": "3",
            "shg_role": "2",
            "shg_id": "12",
            "pip_category": "MIDDLECLASS",
            "disability": 0,
            "religion": "2",
            "apl": 0
        },
             {
            "member_name": "Sanjay",
            "middle_name": "Vijay",
            "email": "sanjay@mail.com",
            "contact_number": "1234",
           "village":"kjdk",
            "local_body":"232",
            "block":"2323",
            "district": "23",
            "state": "23",
            "zip_code": "2134",
            "gender": "male",
            "dob": "2022-12-23",
            "social_category": "1",
            "skills": ["html","css","js"],
            "experience": "Carpentar",
            "experience_year": "3",
            "shg_role": "3",
            "shg_id": "12",
            "pip_category": "RICH",
            "disability": 0,
            "religion": "2",
            "apl": 0
        }
    ]
}


```


## Shg profile create

```
{
    "shgprofile": {
        "title": "Test SHG",
        "contact": "123456789",
        "email": "test@gmail.com",
        "address": "test address",
        "village": "Test village",
        "local_body": "123",
        "block": "344",
        "district": "234",
        "state": "23",
        "zip_code": "23456",
        "about_short": "sdn,sdnd,ksm.fd,ms.,dfm.mv",
        "about_me": "asdlfjksdmf.smdf.",
        "ac_name": "Test account",
        "ac_number": "123456890",
        "bank_name": "Test Bank of india",
        "branch_name": "Tester",
        "ifsc_code": "ERFGHJKL",
        "swift_code": "SWIFT35678o",
        "shg_image": "ijdksmd.jpg",
        "shg_feature_image": "ksjdhksdjf.png",
        "registered_by": "2",
        "shg_type": "2",
        "establishment_date": "2023-12-12",
        "group_id": "12"
    },
    "members": [
        {
            "member_name": "Ajay",
            "middle_name": "Vijay",
            "email": "ajay@mail.com",
            "contact_number": "1234",
            "village":"Test village",
            "local_body":"123",
            "block":"344",
           
            "district": "23",
            "state": "23",
            "zip_code": "2134",
            "gender": "male",
            "dob": "2022-12-23",
            "social_category": "1",
            "skills": [
                "html",
                "css"
            ],
            "experience": "Carpentar",
            "experience_year": "3",
            "shg_role": "1",
            "shg_id": "12",
            "pip_category": "POOR",
            "disability": 0,
            "religion": "2",
            "apl": 1
        },
        {
            "member_name": "Vijay",
            "middle_name": "Ajay",
            "email": "vijay@mail.com",
            "contact_number": "1234",
            "village":"Test village",
            "local_body":"123",
            "block":"344",
            
            "district": "23",
            
            "state": "23",
            "zip_code": "2134",
            "gender": "male",
            "dob": "2022-12-23",
            "social_category": "1",
            "skills": [
                "html",
                "css",
                "js"
            ],
            "experience": "Carpentar",
            "experience_year": "3",
            "shg_role": "2",
            "shg_id": "12",
            "pip_category": "MIDDLECLASS",
            "disability": 0,
            "religion": "2",
            "apl": 0
        },
        {
            "member_name": "Sanjay",
            "middle_name": "Vijay",
            "email": "sanjay@mail.com",
            "contact_number": "1234",
             "local_body":"123",
            "village":"Test village",
            "block": "23",
            "district": "23",
            "state": "23",
            "zip_code": "2134",
            "gender": "male",
            "dob": "2022-12-23",
            "social_category": "1",
            "skills": [
                "html",
                "css",
                "js"
            ],
            "experience": "Carpentar",
            "experience_year": "3",
            "shg_role": "3",
            "shg_id": "12",
            "pip_category": "RICH",
            "disability": 0,
            "religion": "2",
            "apl": 0
        }
    ]
}
```
## Customer (get all)
#### URL
```
localhost:8080/getAllCustomers
```
#### Type
```
get
```
#### Response

```
{
    "status": 200,
    "data": {
        "customer": [
            {
                "id": "2",
                "f_name": "as.kamdsd",
                "l_name": "kale_d",
                "company_name": "bright pvt ltd",
                "address": "manurma building , sect-9",
                "city": "vadgao",
                "district": "palam=1",
                "state": "maharashtraas",
                "contact": "9175692384",
                "email": "suresh.s@kitintellect.com",
                "gst_number": "0",
                "shg_id": "34",
                "zip_code": "123456"
            },
            {
                "id": "1",
                "f_name": "sad.,am",
                "l_name": "kalem",
                "company_name": "bright pvt ltd",
                "address": "manurma building , sect-9",
                "city": "vadgao",
                "district": "palam=1",
                "state": "maharashtraas",
                "contact": "9175692384",
                "email": "suresh.s@kitintellect.com",
                "gst_number": "0",
                "shg_id": "34",
                "zip_code": "123456"
            }
        ]
    },
    "error": null
}
```
### Customer (show)
#### URL
```
localhost:8080/customer/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": [
        {
            "id": "1",
            "f_name": "sad.,am",
            "l_name": "kalem",
            "company_name": "bright pvt ltd",
            "address": "manurma building , sect-9",
            "city": "vadgao",
            "district": "palam=1",
            "state": "maharashtraas",
            "contact": "9175692384",
            "email": "suresh.s@kitintellect.com",
            "gst_number": "0",
            "shg_id": "34",
            "zip_code": "123456"
        }
    ],
    "error": null
}
```
### Customer (shgId)
#### URL
```
/customer/shg/{id}
```
#### Type 
```
get
```
#### Response
```
{
    "status": 200,
    "data": [
        {
            "id": "1",
            "f_name": "sad.,am",
            "l_name": "kalem",
            "company_name": "bright pvt ltd",
            "address": "manurma building , sect-9",
            "city": "vadgao",
            "district": "palam=1",
            "state": "maharashtraas",
            "contact": "9175692384",
            "email": "suresh.s@kitintellect.com",
            "gst_number": "0",
            "shg_id": "34",
            "zip_code": "123456"
        },
        {
            "id": "2",
            "f_name": "as.kamdsd",
            "l_name": "kale_d",
            "company_name": "bright pvt ltd",
            "address": "manurma building , sect-9",
            "city": "vadgao",
            "district": "palam=1",
            "state": "maharashtraas",
            "contact": "9175692384",
            "email": "suresh.s@kitintellect.com",
            "gst_number": "0",
            "shg_id": "34",
            "zip_code": "123456"
        }
    ],
    "error": null
}
```
### Customer (create)
#### URL
```
/customer/create
```
#### Type 
```
post
```
#### Payload
```
{
            "f_name": "Suyash",
            "l_name": "Kadam",
            "company_name": "Bright pvt ltd",
            "address": "manurma building , sect-9",
            "city": "Vadgaon",
            "district": "Palam",
            "state": "Maharashtra",
            "contact": "9175692384",
            "email": "suresh.s@kitintellect.com",
            "gst_number": "0",
            "shg_id": "35",
            "zip_code": "123456"
        }
```
#### Response
```
{
    "status": 200,
    "success": "Record created succesfully",
    "data": {
        "id": "0",
        "f_name": "Suyash",
        "l_name": "Kadam",
        "company_name": "Bright pvt ltd",
        "address": "manurma building , sect-9",
        "city": "Vadgaon",
        "district": "Palam",
        "state": "Maharashtra",
        "contact": "9175692384",
        "email": "suresh.s@kitintellect.com",
        "gst_number": "0",
        "shg_id": "35",
        "zip_code": "123456"
    },
    "error": null
}
```
### Customer (update)
#### URL
```
/customer/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
            "f_name": "Suyash",
            "l_name": "Kadam",
            "company_name": "Bright pvt ltd",
            "address": "manurma building , sect-9",
            "city": "Mumbai",
            "district": "Mumbai",
            "state": "Maharashtra",
            "contact": "9175692384",
            "email": "suresh.s@kitintellect.com",
            "gst_number": "1",
            "shg_id": "35",
            "zip_code": "123456"
        }
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "2",
        "f_name": "Suyash",
        "l_name": "Kadam",
        "company_name": "Bright pvt ltd",
        "address": "manurma building , sect-9",
        "city": "Mumbai",
        "district": "Mumbai",
        "state": "Maharashtra",
        "contact": "9175692384",
        "email": "suresh.s@kitintellect.com",
        "gst_number": "1",
        "shg_id": "35",
        "zip_code": "123456"
    },
    "error": null
}
```
### Customer (delete)
#### URL
```
/customer/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "response": "Record successfully deleted"
    }
}
```
### Vendor (get all)
#### URL
```
localhost:8080/getAllVendors
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "vendor": [
            {
                "id": "2",
                "f_name": "gopal",
                "l_name": "ksa",
                "address": "as;m",
                "city": "karepur",
                "state": "as",
                "district": "Budruk",
                "zip_code": "913456",
                "contact": "9175692384",
                "company_name": "bright pvt ltd",
                "shg_id": "94",
                "email": "suresh.s@kitintellect.com"
            },
            {
                "id": "1",
                "f_name": "gopal",
                "l_name": "sonavne",
                "address": "sonavne building , vithal mandir",
                "city": "karepur",
                "state": "maharashtra",
                "district": "Budruk",
                "zip_code": "913456",
                "contact": "9175692384",
                "company_name": "bright pvt ltd",
                "shg_id": "94",
                "email": "suresh.s@kitintellect.com"
            }
        ]
    },
    "error": null
}
```
### Vendor (show)
#### URL
```
/vendor/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": [
        {
            "id": "1",
            "f_name": "gopal",
            "l_name": "sonavne",
            "address": "sonavne building , vithal mandir",
            "city": "karepur",
            "state": "maharashtra",
            "district": "Budruk",
            "zip_code": "913456",
            "contact": "9175692384",
            "company_name": "bright pvt ltd",
            "shg_id": "94",
            "email": "suresh.s@kitintellect.com"
        }
    ],
    "error": null
}
```
### Vendor (shgId)
#### URL
```
/vendor/shg/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": [
        {
            "id": "1",
            "f_name": "gopal",
            "l_name": "sonavne",
            "address": "sonavne building , vithal mandir",
            "city": "karepur",
            "state": "maharashtra",
            "district": "Budruk",
            "zip_code": "913456",
            "contact": "9175692384",
            "company_name": "bright pvt ltd",
            "shg_id": "94",
            "email": "suresh.s@kitintellect.com"
        },
        {
            "id": "2",
            "f_name": "gopal",
            "l_name": "ksa",
            "address": "as;m",
            "city": "karepur",
            "state": "as",
            "district": "Budruk",
            "zip_code": "913456",
            "contact": "9175692384",
            "company_name": "bright pvt ltd",
            "shg_id": "94",
            "email": "suresh.s@kitintellect.com"
        }
    ],
    "error": null
}
```
### Vendor (create)
#### URL
```
/vendor/create
```
#### Type
```
post
```
#### Payload
```
{
    "f_name": "Sumit",
    "l_name": "sonavne",
    "address": "sonavne building , vithal mandir",
    "city": "koregaon",
    "state": "maharashtra",
    "district": "Pune",
    "zip_code": "913456",
    "contact": "9175692384",
    "company_name": "bright pvt ltd",
    "shg_id": "95",
    "email": "suresh.s@kitintellect.com"
}
```
#### Reponse
```
{
    "status": 200,
    "data": {
        "id": "0",
        "f_name": "Sumit",
        "l_name": "sonavne",
        "address": "sonavne building , vithal mandir",
        "city": "koregaon",
        "state": "maharashtra",
        "district": "Pune",
        "zip_code": "913456",
        "contact": "9175692384",
        "company_name": "bright pvt ltd",
        "shg_id": "95",
        "email": "suresh.s@kitintellect.com"
    },
    "error": null
}
```
### Vendor (update)
#### URL
```
/vendor/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
    "f_name": "Sumit",
    "l_name": "sonavne",
    "address": "sonavne building , Near vithal mandir",
    "city": "karegaon",
    "state": "Maharashtra",
    "district": "Pune",
    "zip_code": "913456",
    "contact": "9175692384",
    "company_name": "bright pvt ltd",
    "shg_id": "96",
    "email": "suresh.s@kitintellect.com"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "0",
        "f_name": "Sumit",
        "l_name": "sonavne",
        "address": "sonavne building , Near vithal mandir",
        "city": "karegaon",
        "state": "Maharashtra",
        "district": "Pune",
        "zip_code": "913456",
        "contact": "9175692384",
        "company_name": "bright pvt ltd",
        "shg_id": "96",
        "email": "suresh.s@kitintellect.com"
    },
    "error": null
}
```
### Vendor (delete)
#### URL
```
/vendor/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "success": "Vendor successfully deleted"
    }
}
```
### Business loan (list all)
#### URL
```
/businessloan/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "business_loan": [
            {
                "id": "8",
                "applied_loan_amount": "450000",
                "customer_occupation": "manager",
                "monthly_salary": "45000",
                "customer_full_name": "Vinay Shriram Patil",
                "customer_contact_number": "2147483647",
                "customer_email_id": "vinod1@gmail.com",
                "customer_address": "Sarda Nagri",
                "zip_code": "123456",
                "state": "Maharashtra",
                "district": "Pune",
                "customer_marital_status": "married",
                "customer_dob": "1994-02-22",
                "customer_gender": "Male",
                "owenership_of_home": "yes",
                "duration_of_stying": "15years",
                "agent_referal_id": "1",
                "office_name": "Kepro pvt ltd",
                "official_address": "durg highway, petrol pump",
                "official_zip_code": "284736",
                "official_state": "madhypradesh",
                "official_district": "bhopal",
                "official_email_id": "vinod@melton.in",
                "experiance_in_current_company": "3",
                "total_work_experiance": "5",
                "addhar_card": "adhar.jpg",
                "pan_card": "pan.jpg",
                "passport_size_photo": "paspport.jpg",
                "salary_slip1_month": "sla1.jpg",
                "salary_slip2_month": "sal2.jpg",
                "salary_slip3_month": "sal3.jpg",
                "bank_statement": "bank.jpg"
            },
            {
                "id": "2",
                "applied_loan_amount": "1000000",
                "customer_occupation": "business",
                "monthly_salary": "60000",
                "customer_full_name": "mathur gajodhar patel",
                "customer_contact_number": "2147483647",
                "customer_email_id": "mathur@gmail.com",
                "customer_address": "kartavy nagari",
                "zip_code": "784627",
                "state": "madhypradesh",
                "district": "bhopal",
                "customer_marital_status": "marid",
                "customer_dob": "1992-02-22",
                "customer_gender": "male",
                "owenership_of_home": "yes",
                "duration_of_stying": "10years",
                "agent_referal_id": "0",
                "office_name": "meltone pvt ltd",
                "official_address": "durg highway, petrol pump",
                "official_zip_code": "284736",
                "official_state": "madhypradesh",
                "official_district": "bhopal",
                "official_email_id": "mathur@melton.in",
                "experiance_in_current_company": "3",
                "total_work_experiance": "5",
                "addhar_card": "adhar.jpg",
                "pan_card": "pan.jpg",
                "passport_size_photo": "paspport.jpg",
                "salary_slip1_month": "sla1.jpg",
                "salary_slip2_month": "sal2.jpg",
                "salary_slip3_month": "sal3.jpg",
                "bank_statement": "bank.jpg"
            },
            {
                "id": "1",
                "applied_loan_amount": "500000",
                "customer_occupation": "manager",
                "monthly_salary": "30000",
                "customer_full_name": "vinod gajodhar patel",
                "customer_contact_number": "2147483647",
                "customer_email_id": "vinod1@gmail.com",
                "customer_address": "kartavy nagari",
                "zip_code": "784627",
                "state": "madhypradesh",
                "district": "bhopal",
                "customer_marital_status": "marid",
                "customer_dob": "1992-02-22",
                "customer_gender": "male",
                "owenership_of_home": "yes",
                "duration_of_stying": "10years",
                "agent_referal_id": "0",
                "office_name": "meltone pvt ltd",
                "official_address": "durg highway, petrol pump",
                "official_zip_code": "284736",
                "official_state": "madhypradesh",
                "official_district": "bhopal",
                "official_email_id": "vinod@melton.in",
                "experiance_in_current_company": "3",
                "total_work_experiance": "5",
                "addhar_card": "adhar.jpg",
                "pan_card": "pan.jpg",
                "passport_size_photo": "paspport.jpg",
                "salary_slip1_month": "sla1.jpg",
                "salary_slip2_month": "sal2.jpg",
                "salary_slip3_month": "sal3.jpg",
                "bank_statement": "bank.jpg"
            }
        ]
    },
    "error": null
}
```
### Business loan (show)
#### URL
```
/businessloan/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": [
        {
            "id": "1",
            "applied_loan_amount": "500000",
            "customer_occupation": "manager",
            "monthly_salary": "30000",
            "customer_full_name": "vinod gajodhar patel",
            "customer_contact_number": "2147483647",
            "customer_email_id": "vinod1@gmail.com",
            "customer_address": "kartavy nagari",
            "zip_code": "784627",
            "state": "madhypradesh",
            "district": "bhopal",
            "customer_marital_status": "marid",
            "customer_dob": "1992-02-22",
            "customer_gender": "male",
            "owenership_of_home": "yes",
            "duration_of_stying": "10years",
            "agent_referal_id": "0",
            "office_name": "meltone pvt ltd",
            "official_address": "durg highway, petrol pump",
            "official_zip_code": "284736",
            "official_state": "madhypradesh",
            "official_district": "bhopal",
            "official_email_id": "vinod@melton.in",
            "experiance_in_current_company": "3",
            "total_work_experiance": "5",
            "addhar_card": "adhar.jpg",
            "pan_card": "pan.jpg",
            "passport_size_photo": "paspport.jpg",
            "salary_slip1_month": "sla1.jpg",
            "salary_slip2_month": "sal2.jpg",
            "salary_slip3_month": "sal3.jpg",
            "bank_statement": "bank.jpg"
        }
    ],
    "error": null
}
```
### Business loan (create)
#### URL
```
/businessloan/create
```
#### Type
```
post
```
#### Payload
```
{
            "applied_loan_amount": "450000",
            "customer_occupation": "manager",
            "monthly_salary": "40000",
            "customer_full_name": "vinod gajodhar patel",
            "customer_contact_number": "2147483647",
            "customer_email_id": "vinod1@gmail.com",
            "customer_address": "Sarda Nagri",
            "zip_code": "123456",
            "state": "Maharashtra",
            "district": "Pune",
            "customer_marital_status": "married",
            "customer_dob": "1994-02-22",
            "customer_gender": "Male",
            "owenership_of_home": "yes",
            "duration_of_stying": "15years",
            "agent_referal_id": "1",
            "office_name": "Kepro pvt ltd",
            "official_address": "durg highway, petrol pump",
            "official_zip_code": "284736",
            "official_state": "madhypradesh",
            "official_district": "bhopal",
            "official_email_id": "vinod@melton.in",
            "experiance_in_current_company": "3",
            "total_work_experiance": "5",
            "addhar_card": "adhar.jpg",
            "pan_card": "pan.jpg",
            "passport_size_photo": "paspport.jpg",
            "salary_slip1_month": "sla1.jpg",
            "salary_slip2_month": "sal2.jpg",
            "salary_slip3_month": "sal3.jpg",
            "bank_statement": "bank.jpg"
        } 
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "8",
        "applied_loan_amount": "450000",
        "customer_occupation": "manager",
        "monthly_salary": "40000",
        "customer_full_name": "vinod gajodhar patel",
        "customer_contact_number": "2147483647",
        "customer_email_id": "vinod1@gmail.com",
        "customer_address": "Sarda Nagri",
        "zip_code": "123456",
        "state": "Maharashtra",
        "district": "Pune",
        "customer_marital_status": "married",
        "customer_dob": "1994-02-22",
        "customer_gender": "Male",
        "owenership_of_home": "yes",
        "duration_of_stying": "15years",
        "agent_referal_id": "1",
        "office_name": "Kepro pvt ltd",
        "official_address": "durg highway, petrol pump",
        "official_zip_code": "284736",
        "official_state": "madhypradesh",
        "official_district": "bhopal",
        "official_email_id": "vinod@melton.in",
        "experiance_in_current_company": "3",
        "total_work_experiance": "5",
        "addhar_card": "adhar.jpg",
        "pan_card": "pan.jpg",
        "passport_size_photo": "paspport.jpg",
        "salary_slip1_month": "sla1.jpg",
        "salary_slip2_month": "sal2.jpg",
        "salary_slip3_month": "sal3.jpg",
        "bank_statement": "bank.jpg"
    },
    "error": null
}
```
### Busniess loan (update)
#### URL
```
/businessloan/update/{id}
```
#### Type
```
patch
```
#### Paylaod
```
{
            "applied_loan_amount": "450000",
            "customer_occupation": "manager",
            "monthly_salary": "45000",
            "customer_full_name": "Vinay Shriram Patil",
            "customer_contact_number": "2147483647",
            "customer_email_id": "vinod1@gmail.com",
            "customer_address": "Sarda Nagri",
            "zip_code": "123456",
            "state": "Maharashtra",
            "district": "Pune",
            "customer_marital_status": "married",
            "customer_dob": "1994-02-22",
            "customer_gender": "Male",
            "owenership_of_home": "yes",
            "duration_of_stying": "15years",
            "agent_referal_id": "1",
            "office_name": "Kepro pvt ltd",
            "official_address": "durg highway, petrol pump",
            "official_zip_code": "284736",
            "official_state": "madhypradesh",
            "official_district": "bhopal",
            "official_email_id": "vinod@melton.in",
            "experiance_in_current_company": "3",
            "total_work_experiance": "5",
            "addhar_card": "adhar.jpg",
            "pan_card": "pan.jpg",
            "passport_size_photo": "paspport.jpg",
            "salary_slip1_month": "sla1.jpg",
            "salary_slip2_month": "sal2.jpg",
            "salary_slip3_month": "sal3.jpg",
            "bank_statement": "bank.jpg"
        }
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "8",
        "applied_loan_amount": "450000",
        "customer_occupation": "manager",
        "monthly_salary": "45000",
        "customer_full_name": "Vinay Shriram Patil",
        "customer_contact_number": "2147483647",
        "customer_email_id": "vinod1@gmail.com",
        "customer_address": "Sarda Nagri",
        "zip_code": "123456",
        "state": "Maharashtra",
        "district": "Pune",
        "customer_marital_status": "married",
        "customer_dob": "1994-02-22",
        "customer_gender": "Male",
        "owenership_of_home": "yes",
        "duration_of_stying": "15years",
        "agent_referal_id": "1",
        "office_name": "Kepro pvt ltd",
        "official_address": "durg highway, petrol pump",
        "official_zip_code": "284736",
        "official_state": "madhypradesh",
        "official_district": "bhopal",
        "official_email_id": "vinod@melton.in",
        "experiance_in_current_company": "3",
        "total_work_experiance": "5",
        "addhar_card": "adhar.jpg",
        "pan_card": "pan.jpg",
        "passport_size_photo": "paspport.jpg",
        "salary_slip1_month": "sla1.jpg",
        "salary_slip2_month": "sal2.jpg",
        "salary_slip3_month": "sal3.jpg",
        "bank_statement": "bank.jpg"
    },
    "error": null
}
```
### Business loan (delete)
#### URL
```
/businessloan/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "success": "Business deleted successfully"
    }
}
```
### Business Members (create)
#### URL
```
localhost:8080/businessmembers/create
```
#### Type
```
post
```
#### Payload
```
{
    "name":"Riya Kulkarni",
    "email":"riya1.kulkarni@gmail.com",
    "gender":"Female",
    "dob":"1992/04/12",
    "business_role":"Member"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "4",
        "name": "Riya Kulkarni",
        "email": "riya1.kulkarni@gmail.com",
        "gender": "Female",
        "dob": "1992",
        "business_role": "Member"
    },
    "error": null
}
```

### Business Members (show)
#### URL
```
/businessmembers/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "2",
        "name": "Riya Kulkarni",
        "email": "riya1.kulkarni@gmail.com",
        "gender": "Female",
        "dob": "1992",
        "business_role": "Member"
    },
    "error": null
}
```
### Business Members (update)
#### URL
```
businessmembers/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
    "name":"Riya Kulkarni",
    "email":"riya1.kulkarni@gmail.com",
    "gender":"Female",
    "dob":"1992/04/12",
    "business_role":"Member"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "2",
        "name": "Riya Kulkarni",
        "email": "riya1.kulkarni@gmail.com",
        "gender": "Female",
        "dob": "1992",
        "business_role": "Member"
    },
    "error": null
}
```
### Business Members (delete)
#### URL
```
/businessmembers/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "response": "Record deleted successfully"
    }
}
```
### Business Members (list all)
#### URL
```
/businessmembers/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "business_members": [
            {
                "id": "4",
                "name": "Riya Kulkarni",
                "email": "riya1.kulkarni@gmail.com",
                "gender": "Female",
                "dob": "1992",
                "business_role": "Member"
            },
            {
                "id": "3",
                "name": "Riya Kulkarni",
                "email": "riya1.kulkarni@gmail.com",
                "gender": "Female",
                "dob": "1992",
                "business_role": "Member"
            },
            {
                "id": "2",
                "name": "Riya Kulkarni",
                "email": "riya1.kulkarni@gmail.com",
                "gender": "Female",
                "dob": "1992",
                "business_role": "Member"
            }
        ]
    },
    "error": null
}
```
### Business Member Roles (create)
#### URL
```
/businessmembersrole/create
```
#### Type
```
post
```
#### Payload
```
{
    "role_name":"Nikita"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "5",
        "role_name": "Nikita",
        "access": null
    },
    "error": null
}
```
### Business Member Roles (show)
#### URL
```
/businessmembersrole/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "1",
        "role_name": "Vaibhav",
        "access": ""
    },
    "error": null
}
```
### Business Member Roles (update)
#### URL
```
/businessmembersrole/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
    "role_name":"Kartiki"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "4",
        "role_name": "Kartiki",
        "access": null
    },
    "error": null
}
```
### Business Member Roles (delete)
#### URL
```
/businessmembersrole/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "response": "Record deleted successfully"
    }
}
```
### Business Member Roles (list all)
#### URL
```
/businessmembersrole/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "business_member_roles": [
            {
                "id": "5",
                "role_name": "Nikita",
                "access": null
            },
            {
                "id": "4",
                "role_name": "Kartiki",
                "access": null
            },
            {
                "id": "1",
                "role_name": "Vaibhav",
                "access": ""
            }
        ]
    },
    "error": null
}
```
### Product (create)
#### URL
```
/product/create
```
#### Type
```
post
```
#### Payload
```
{
            "product_name": "Noodles",
            "price": "80",
            "sales_price": "70",
            "description": "Sweet n spicy",
            "short_description": "it is very Tastey",
            "feature_image": "dd.jpg",
            "image_gallary": "mm.jpg",
            "shg_id": "83",
            "category_id": "0"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "6",
        "product_name": "Noodles",
        "price": "0",
        "sales_price": "0",
        "description": "Sweet n spicy",
        "short_description": "it is very Tastey",
        "feature_image": "dd.jpg",
        "image_gallary": "mm.jpg",
        "shg_id": "83",
        "category_id": "0"
    },
    "error": null
}
```
### Product (show)
#### URL
```
/product/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": [
        {
            "id": "4",
            "product_name": "Magge",
            "price": "0",
            "sales_price": "0",
            "description": "Sweet n spicy",
            "short_description": "it is very Tastey",
            "feature_image": "dd.jpg",
            "image_gallary": "mm.jpg",
            "shg_id": "83",
            "category_id": "0"
        }
    ],
    "error": null
}
```
### Product (update)
#### URL
```
/product/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
            "product_name": "Maggie",
            "price": "80",
            "sales_price": "70",
            "description": "Sweet n spicy",
            "short_description": "it is very Tastey",
            "feature_image": "dd.jpg",
            "image_gallary": "mm.jpg",
            "shg_id": "83",
            "category_id": "5"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "4",
        "product_name": "Maggie",
        "price": "0",
        "sales_price": "0",
        "description": "Sweet n spicy",
        "short_description": "it is very Tastey",
        "feature_image": "dd.jpg",
        "image_gallary": "mm.jpg",
        "shg_id": "83",
        "category_id": "0"
    },
    "error": null
}
```
### Product (delete)
#### URL
```
/product/delete/{id}
```
#### Type
``` 
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "success": "Product deleted successfully"
    }
}
```

### Shg Loans (create)
#### URL
```
/shgloans/create
```
#### Type
```
post
```
#### Payload
```
{
    "shg_id": "23",
 "member_id": "23",
 "payment_method": "1",
 "transaction_id": "2sdkfjsdf",
 "loan_starting_date": "2020-12-29",
 "loan_end_date": "2022-12-29",
 "principle_amount": "12000",
 "tenure_year": "1",
 "tenure_month": "2",
 "interest_month": "2",
   "added_by" : 33
}
```
#### Response
```
{
    "status": 200,
    "message": "Record added successfully",
    "data": {
        "id": "6",
        "loan_id": "asm:01:12:22:06:34:39:23:23",
        "emi": "891.43",
        "principle_amount": "12000",
        "interest_amount": "480",
        "total_payable": "12480",
        "remaining_amount": "12480",
        "loan_status": "1",
        "created_at": "2022-12-01 18:04:39"
    }
}
```
## Trainer (create)
#### URL
```
/trainer/create
```
#### Type
```
post
```
#### Payload
```
{
    "name":"Raman", 
     "experties":"Making papad",
    "categories":"Food", 
    "experience":"4", 
    "contact":"1334567890", 
    "email":"raman@gmail.com", 
    "address":"Pune", 
    "avtar":"dd.jpg",
    "organisation":"SHG"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "6",
        "name": "Raman",
        "experties": "Making papad",
        "categories": "Food",
        "experience": "4",
        "contact": "1334567890",
        "email": "raman@gmail.com",
        "address": "Pune",
        "avtar": "dd.jpg",
        "organisation": "SHG"
    },
    "error": null
}
```
## Trainer (read)
#### URL
```
/trainer/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "6",
        "name": "Raman",
        "experties": "Making papad",
        "categories": "Food",
        "experience": "4",
        "contact": "1334567890",
        "email": "raman@gmail.com",
        "address": "Pune",
        "avtar": "dd.jpg",
        "organisation": "SHG"
    },
    "error": null
}
```
## Trainer (update)
#### URL
```
/trainer/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
    "name":"Komal", 
     "experties":"Cooking",
    "categories":"Food", 
    "experience":"5", 
    "contact":"1334567890", 
    "email":"komal@gmail.com", 
    "address":"Pune", 
    "avtar":"mm.jpg",
    "organisation":"SHG"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "4",
        "name": "Komal",
        "experties": "Cooking",
        "categories": "Food",
        "experience": "5",
        "contact": "1334567890",
        "email": "komal@gmail.com",
        "address": "Pune",
        "avtar": "mm.jpg",
        "organisation": "SHG"
    },
    "error": null
}
```
## Trainer(delete)
#### URL
```
/trainer/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "response": "Record successfully deleted"
    }
}
```
## Trainer (list all)
#### URL
```
/trainer/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "trainer": [
            {
                "id": "6",
                "name": "Raman",
                "experties": "Making papad",
                "categories": "Food",
                "experience": "4",
                "contact": "1334567890",
                "email": "raman@gmail.com",
                "address": "Pune",
                "avtar": "dd.jpg",
                "organisation": "SHG"
            },
            {
                "id": "4",
                "name": "Komal",
                "experties": "Cooking",
                "categories": "Food",
                "experience": "5",
                "contact": "1334567890",
                "email": "komal@gmail.com",
                "address": "Pune",
                "avtar": "mm.jpg",
                "organisation": "SHG"
            },
            {
                "id": "3",
                "name": "Raman",
                "experties": "Making papad",
                "categories": "Food",
                "experience": "4",
                "contact": "1334567890",
                "email": "raman@gmail.com",
                "address": "Nagpur",
                "avtar": "dd.jpg",
                "organisation": "SHG"
            }
        ]
    },
    "error": null
}
```
## Workshop (create)
#### URL
```
/workshop/create
```
#### Type
```
post
```
#### Payload
```
{
    "title":"SHG Workhop 2", 
    "category":"Cooking", 
    "short_desc":"In this workshop we will see what to cook in this type of workshop", 
    "date":"2012-05-21",
    "time":"07:25:44"
    
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "8",
        "title": "SHG Workhop 2",
        "category": "Cooking",
        "short_desc": "In this workshop we will see what to cook in this type of workshop",
        "date": "2012-05-21",
        "time": "07:25:44",
        "created_at": "2022-12-05 18:23:17"
    },
    "error": null
}
```
## Workshop (read)
#### URL
```
/workshop/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "5",
        "title": "SHG Workhop 1 ",
        "category": "Banking",
        "short_desc": "In this workshop we will see how to fill passbook",
        "date": "2012-04-02",
        "time": "13:00:45",
        "created_at": "2022-12-05 17:29:06"
    },
    "error": null
}
```
## Workshop (update)
#### URL
```
/workshop/update{id}
```
#### Type
```
patch
```
#### Payload
```
{
        "title": "SHG Workhop 1 ",
        "category": "Banking",
        "short_desc": "In this workshop we will see how to fill passbook",
        "date": "2012-04-02",
        "time": "13:00:45"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "5",
        "title": "SHG Workhop 1 ",
        "category": "Banking",
        "short_desc": "In this workshop we will see how to fill passbook",
        "date": "2012-04-02",
        "time": "13:00:45",
        "created_at": "2022-12-05 17:29:06"
    },
    "error": null
}
```
## Workshop (delete)
#### URL
```
/workshop/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "response": "Record successfully deleted"
    }
}
```
## Workshop (list all)
#### URL
```
/workshop/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "trainer": [
            {
                "id": "6",
                "title": "SHG Workhop 2",
                "category": "Cooking",
                "short_desc": "In this workshop we will see what to cook in this type of workshop",
                "date": "2012-05-21",
                "time": "07:25:44",
                "created_at": "2022-12-05 17:29:12"
            },
            {
                "id": "5",
                "title": "SHG Workhop 1 ",
                "category": "Banking",
                "short_desc": "In this workshop we will see how to fill passbook",
                "date": "2012-04-02",
                "time": "13:00:45",
                "created_at": "2022-12-05 17:29:06"
            }
        ]
    },
    "error": null
}
```
## Admin products (create)
#### URL
```
/adminproducts/create
```
#### Type
```
post
```
#### Payload
```
{
            "product_name": "Noodles",
            "price": "80",
            "sales_price": "70",
            "description": "Sweet n spicy",
            "short_description": "it is very Tastey",
            "feature_image": "dd.jpg",
            "image_gallery": "mm.jpg",
            "user_id": "124",
            "category_id": "0"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "5",
        "product_name": "Noodles",
        "price": "80",
        "sales_price": "70",
        "description": "Sweet n spicy",
        "short_description": "it is very Tastey",
        "feature_image": "dd.jpg",
        "image_gallery": "mm.jpg",
        "user_id": "124",
        "category_id": "0"
    },
    "error": null
}
```
## Admin products (read)
#### URL
```
/adminproducts/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": [
        {
            "id": "1",
            "product_name": "chair",
            "price": "400",
            "sales_price": "500",
            "description": "chairs for office",
            "short_description": "white and black coloured",
            "feature_image": "dd.jpg",
            "image_gallery": "mm.jpg",
            "user_id": "122",
            "category_id": "0"
        }
    ],
    "error": null
}
```
## Admin products (update)
#### URL
```
/adminproducts/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
        "product_name": "bottle",
        "price": "100",
        "sales_price": "150",
        "description": "lightweight",
        "short_description": "reusable",
        "feature_image": "dd.jpg",
        "image_gallery": "mm.jpg",
        "user_id": "124",
        "category_id": "0"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "3",
        "product_name": "bottle",
        "price": "100",
        "sales_price": "150",
        "description": "lightweight",
        "short_description": "reusable",
        "feature_image": "dd.jpg",
        "image_gallery": "mm.jpg",
        "user_id": "124",
        "category_id": "0"
    },
    "error": null
}
```
## Admin products (delete)
#### URL
```
adminproducts/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "success": "User deleted successfully"
    }
}
```
## Admin products (list all)
#### URL
```
/adminproducts/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "admin_products": [
            {
                "id": "5",
                "product_name": "Noodles",
                "price": "80",
                "sales_price": "70",
                "description": "Sweet n spicy",
                "short_description": "it is very Tastey",
                "feature_image": "dd.jpg",
                "image_gallery": "mm.jpg",
                "user_id": "124",
                "category_id": "0"
            },
            {
                "id": "4",
                "product_name": "Noodles",
                "price": "80",
                "sales_price": "70",
                "description": "Sweet n spicy",
                "short_description": "it is very Tastey",
                "feature_image": "dd.jpg",
                "image_gallery": "mm.jpg",
                "user_id": "124",
                "category_id": "0"
            },
            {
                "id": "3",
                "product_name": "bottle",
                "price": "100",
                "sales_price": "150",
                "description": "lightweight",
                "short_description": "reusable",
                "feature_image": "dd.jpg",
                "image_gallery": "mm.jpg",
                "user_id": "124",
                "category_id": "0"
            },
            {
                "id": "1",
                "product_name": "bottle",
                "price": "150",
                "sales_price": "150",
                "description": "lightweight",
                "short_description": "reusable",
                "feature_image": "dd.jpg",
                "image_gallery": "mm.jpg",
                "user_id": "124",
                "category_id": "0"
            }
        ]
    },
    "error": null
} 
```
## Vendor Products (create)
### URL
```
/vendorproducts/create
```
### Type
```
post
```
### Payload
```
{
            "product_name": "chair",
            "price": "400",
            "sales_price": "500",
            "description": "chairs for office",
            "short_description": "white and black coloured",
            "feature_image": "dd.jpg",
            "image_gallery": "mm.jpg",
            "vendor_id": "1005",
            "category_id": "0"
        }
```
### Response
```
{
    "status": 200,
    "data": {
        "id": "5",
        "product_name": "chair",
        "price": "400",
        "sales_price": "500",
        "description": "chairs for office",
        "short_description": "white and black coloured",
        "feature_image": "dd.jpg",
        "image_gallery": "mm.jpg",
        "vendor_id": "1005",
        "category_id": "0"
    },
    "error": null
}
```
## Vendor Products (read)
### URL
```
/vendorproducts/{id}
```
### Type
```
get
```
### Response
```
{
"status": 200,
    "data": [
        {
            "id": "2",
            "product_name": "facewash",
            "price": "200",
            "sales_price": "350",
            "description": "chamical free ,natural ingredients used,soap free",
            "short_description": "fresh",
            "feature_image": "dd.jpg",
            "image_gallery": "mm.jpg",
            "vendor_id": "1002",
            "category_id": "0"
        }
    ],
    "error": null
}
```
## Vendor Products (update)
### URL
```
/vendorproducts/update/{id}
```
### Type
```
patch
```
### Payload
```
{
            "product_name": "cleaner",
            "price": "500",
            "sales_price": "850",
            "description": "chamical free ,natural ingredients used,soap free",
            "short_description": "fresh",
            "feature_image": "dd.jpg",
            "image_gallery": "mm.jpg",
            "vendor_id": "1002",
            "category_id": "0"
}
```
### Response
```
{
    "status": 200,
    "data": {
        "id": "2",
        "product_name": "cleaner",
        "price": "500",
        "sales_price": "850",
        "description": "chamical free ,natural ingredients used,soap free",
        "short_description": "fresh",
        "feature_image": "dd.jpg",
        "image_gallery": "mm.jpg",
        "vendor_id": "1002",
        "category_id": "0"
    },
    "error": null
}
```
## Vendor Products (delete)
### URL
```
/vendorproducts/delete/{id}
```
### Type
```
delete
```
### Response
```
{
    "status": 504,
    "data": null,
    "messages": {
        "success": "user deleted sucessfully"
    }
}
```
## Vendor Products (list all)
### URL
```
/vendorproducts/listAll
```
### Type
```
get
```
### Response
```
{
    "status": 200,
    "data": {
        "vendor_products": [
            {
                "id": "5",
                "product_name": "facewash",
                "price": "200",
                "sales_price": "350",
                "description": "chamical free ,natural ingredients used,soap free",
                "short_description": "fresh",
                "feature_image": "dd.jpg",
                "image_gallery": "mm.jpg",
                "vendor_id": "1005",
                "category_id": "0"
            },
            {
                "id": "4",
                "product_name": "facewash",
                "price": "200",
                "sales_price": "350",
                "description": "chamical free ,natural ingredients used,soap free",
                "short_description": "fresh",
                "feature_image": "dd.jpg",
                "image_gallery": "mm.jpg",
                "vendor_id": "1003",
                "category_id": "0"
            },
            {
                "id": "2",
                "product_name": "cleaner",
                "price": "500",
                "sales_price": "850",
                "description": "chamical free ,natural ingredients used,soap free",
                "short_description": "fresh",
                "feature_image": "dd.jpg",
                "image_gallery": "mm.jpg",
                "vendor_id": "1002",
                "category_id": "0"
            },
            {
                "id": "1",
                "product_name": "facewash",
                "price": "200",
                "sales_price": "350",
                "description": "chamical free ,natural ingredients used,soap free",
                "short_description": "fresh",
                "feature_image": "dd.jpg",
                "image_gallery": "mm.jpg",
                "vendor_id": "1001",
                "category_id": "0"
            }
        ]
    },
    "error": null
}
```
### Personal Loan (create)
#### URL
```
/personalloan/create
```
#### Type
```
post
```
#### Payload
```
{
     "applied_loan_amount": "350000",
        "customer_occupation": "Team member",
        "monthly_salary": "28000",
        "customer_full_name": "Sumit Jadhav",
        "customer_contact_number": "2147483647",
        "customer_email_id": "sumitj@gmail.com",
        "customer_address": "Mumbai",
        "zip_code": "284919",
        "state": "Maharashtra",
        "district": "Mumbai",
        "customer_marital_status": "unmaried",
        "customer_dob": "1990-12-31",
        "customer_gender": "male",
        "children": "0",
        "owenership_of_home": "no",
        "duration_of_stying": "6",
        "agent_referal_id": "rd45he4j5d1",
        "office_name": "bright pvt ltd",
        "official_address": "bright park, relway station",
        "official_zip_code": "482719",
        "official_state": "maharashtra",
        "official_district": "Pune",
        "official_email_id": "amolbright@gmail.com",
        "experiance_in_current_company": "3",
        "total_work_experiance": "4",
        "addhar_card": "adhar.jpg",
        "pan_card": "pan.jpg",
        "passport_size_photo": "passport.jpg",
        "salary_slip1_month": "sal1month.jpg",
        "salary_slip2_month": "sal2month.jpg",
        "salary_slip3_month": "sal3month.jpg",
        "bank_statement": "bank.jpg"
    
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "12",
        "applied_loan_amount": "350000",
        "customer_occupation": "Team member",
        "monthly_salary": "28000",
        "customer_full_name": "Sumit Jadhav",
        "customer_contact_number": "2147483647",
        "customer_email_id": "sumitj@gmail.com",
        "customer_address": "Mumbai",
        "zip_code": "284919",
        "state": "Maharashtra",
        "district": "Mumbai",
        "customer_marital_status": "unmaried",
        "customer_dob": "1990-12-31",
        "customer_gender": "male",
        "children": "0",
        "owenership_of_home": "no",
        "duration_of_stying": "6",
        "agent_referal_id": "rd45he4j5d1",
        "office_name": "bright pvt ltd",
        "official_address": "bright park, relway station",
        "official_zip_code": "482719",
        "official_state": "maharashtra",
        "official_district": "Pune",
        "official_email_id": "amolbright@gmail.com",
        "experiance_in_current_company": "3",
        "total_work_experiance": "4",
        "addhar_card": "adhar.jpg",
        "pan_card": "pan.jpg",
        "passport_size_photo": "passport.jpg",
        "salary_slip1_month": "sal1month.jpg",
        "salary_slip2_month": "sal2month.jpg",
        "salary_slip3_month": "sal3month.jpg",
        "bank_statement": "bank.jpg"
    },
    "error": null
}
```
### Personal Loan (read)
#### URL
```
/personalloan/{id}
```
#### Type
```
get
```
#### Response
```
[
    {
        "id": "1",
        "applied_loan_amount": "350000",
        "customer_occupation": "Team Leader",
        "monthly_salary": "28000",
        "customer_full_name": "vithal devdhar mane",
        "customer_contact_number": "2147483647",
        "customer_email_id": "vithal@gmail.com",
        "customer_address": "modern garden, kalewadi",
        "zip_code": "284919",
        "state": "maharashtra",
        "district": "dhule",
        "customer_marital_status": "unmaried",
        "customer_dob": "1990-12-31",
        "customer_gender": "male",
        "children": "0",
        "owenership_of_home": "no",
        "duration_of_stying": "6",
        "agent_referal_id": "rd45he4j5d1",
        "office_name": "bright pvt ltd",
        "official_address": "bright park, relway station",
        "official_zip_code": "482719",
        "official_state": "maharashtra",
        "official_district": "dhule",
        "official_email_id": "vithalbright@gmail.com",
        "experiance_in_current_company": "3",
        "total_work_experiance": "4",
        "addhar_card": "adhar.jpg",
        "pan_card": "pan.jpg",
        "passport_size_photo": "passport.jpg",
        "salary_slip1_month": "sal1month.jpg",
        "salary_slip2_month": "sal2month.jpg",
        "salary_slip3_month": "sal3month.jpg",
        "bank_statement": "bank.jpg"
    }
]
```
### Personal Loan (update)
#### URL
```
/personalloan/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
     "applied_loan_amount": "480000",
        "customer_occupation": "Team Manager",
        "monthly_salary": "30000",
        "customer_full_name": "Amol Joshi  ",
        "customer_contact_number": "2147483647",
        "customer_email_id": "amolj@gmail.com",
        "customer_address": "Pune",
        "zip_code": "284919",
        "state": "Maharashtra",
        "district": "Pune",
        "customer_marital_status": "unmaried",
        "customer_dob": "1990-12-31",
        "customer_gender": "male",
        "children": "0",
        "owenership_of_home": "no",
        "duration_of_stying": "6",
        "agent_referal_id": "rd45he4j5d1",
        "office_name": "bright pvt ltd",
        "official_address": "bright park, relway station",
        "official_zip_code": "482719",
        "official_state": "maharashtra",
        "official_district": "Pune",
        "official_email_id": "amolbright@gmail.com",
        "experiance_in_current_company": "3",
        "total_work_experiance": "4",
        "addhar_card": "adhar.jpg",
        "pan_card": "pan.jpg",
        "passport_size_photo": "passport.jpg",
        "salary_slip1_month": "sal1month.jpg",
        "salary_slip2_month": "sal2month.jpg",
        "salary_slip3_month": "sal3month.jpg",
        "bank_statement": "bank.jpg"
    
}
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "success": "Personal loan updated successfully"
    }
}
```
### Personal Loan (delete)
#### URL
```
/personalloan/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "response": "Record successfully deleted"
    }
}
```
### Personal Loan (list all)
#### URL
```
/personalloan/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "personal_loan": [
            {
                "id": "11",
                "applied_loan_amount": "350000",
                "customer_occupation": "Team member",
                "monthly_salary": "28000",
                "customer_full_name": "Sumit Jadhav",
                "customer_contact_number": "2147483647",
                "customer_email_id": "sumitj@gmail.com",
                "customer_address": "Mumbai",
                "zip_code": "284919",
                "state": "Maharashtra",
                "district": "Mumbai",
                "customer_marital_status": "unmaried",
                "customer_dob": "1990-12-31",
                "customer_gender": "male",
                "children": "0",
                "owenership_of_home": "no",
                "duration_of_stying": "6",
                "agent_referal_id": "rd45he4j5d1",
                "office_name": "bright pvt ltd",
                "official_address": "bright park, relway station",
                "official_zip_code": "482719",
                "official_state": "maharashtra",
                "official_district": "Pune",
                "official_email_id": "amolbright@gmail.com",
                "experiance_in_current_company": "3",
                "total_work_experiance": "4",
                "addhar_card": "adhar.jpg",
                "pan_card": "pan.jpg",
                "passport_size_photo": "passport.jpg",
                "salary_slip1_month": "sal1month.jpg",
                "salary_slip2_month": "sal2month.jpg",
                "salary_slip3_month": "sal3month.jpg",
                "bank_statement": "bank.jpg"
            },
            {
                "id": "1",
                "applied_loan_amount": "480000",
                "customer_occupation": "Team Manager",
                "monthly_salary": "30000",
                "customer_full_name": "Amol Joshi ",
                "customer_contact_number": "2147483647",
                "customer_email_id": "amolj@gmail.com",
                "customer_address": "Pune",
                "zip_code": "284919",
                "state": "Maharashtra",
                "district": "Pune",
                "customer_marital_status": "unmaried",
                "customer_dob": "1990-12-31",
                "customer_gender": "male",
                "children": "0",
                "owenership_of_home": "no",
                "duration_of_stying": "6",
                "agent_referal_id": "rd45he4j5d1",
                "office_name": "bright pvt ltd",
                "official_address": "bright park, relway station",
                "official_zip_code": "482719",
                "official_state": "maharashtra",
                "official_district": "Pune",
                "official_email_id": "amolbright@gmail.com",
                "experiance_in_current_company": "3",
                "total_work_experiance": "4",
                "addhar_card": "adhar.jpg",
                "pan_card": "pan.jpg",
                "passport_size_photo": "passport.jpg",
                "salary_slip1_month": "sal1month.jpg",
                "salary_slip2_month": "sal2month.jpg",
                "salary_slip3_month": "sal3month.jpg",
                "bank_statement": "bank.jpg"
            }
        ]
    },
    "errors": null
}
```
### Schemes (create)
#### URL
```
/schemes/create
```
#### Type
```
post
```
#### Payload
```
{
    	"title" :"mediacl_help",
    	"short_description":"government",
    	"eligibility":"earning below two lakhs per annum",
    	"benefits":"mediacal",
    	"status":"1"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "2",
        "title": "mediacl_help",
        "short_description": "government",
        "eligibility": "earning below two lakhs per annum",
        "benefits": "",
        "status": "1"
    },
    "error": null
}
```
### Schemes (read)
#### URL
```
/schemes/show/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": [
        {
            "id": "2",
            "title": "old peoples help",
            "short_description": "government",
            "eligibility": "earning below 50k",
            "benefits": "",
            "status": "0"
        }
    ],
    "error": null
}
```
### Schemes (update)
#### URL
```
/schemes/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
    "title" :"old peoples help",
        "short_description":"government",
        "eligibility":"earning below 50k",
        "benefits":"mediacal",
        "status":"0"
}
```
#### Response
```
{
    "status": 200,
    "data": [
        {
            "id": "2",
            "title": "old peoples help",
            "short_description": "government",
            "eligibility": "earning below 50k",
            "benefits": "mediacal",
            "status": "0"
        }
    ],
    "error": null
}
```
### Schemes (delete)
#### URL
```
/schemes/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "success": "User deleted successfully"
    }
}
```
### Schemes (list all)
#### URL
```
/schemes/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "schemes": [
            {
                "id": "4",
                "title": "animals help",
                "short_description": "government scheme",
                "eligibility": "",
                "benefits": "sgdgsuikush",
                "status": "1"
            },
            {
                "id": "3",
                "title": "farmers help",
                "short_description": "farmers helping scheme",
                "eligibility": "",
                "benefits": "",
                "status": "1"
            },
            {
                "id": "1",
                "title": "old peoples help",
                "short_description": "government",
                "eligibility": "earning below 50k",
                "benefits": "",
                "status": "0"
            }
        ]
    },
    "error": null
}
```
### Request Workshop (create)
#### URL
```
/requestworkshop/create
```
#### Type
```
post
```
#### Payload
```
{
    "category":"Cooking",
    "title":"Session", 
    "short_desc":"Will see how to cook different types of cooking"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "3",
        "category": "Cooking",
        "title": "Session",
        "short_desc": "Will see how to cook different types of cooking",
        "created_at": "2022-12-06 17:52:28"
    },
    "message": null
}
```
### Request Workshop (read)
#### URL
```
/requestworkshop/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "2",
        "category": "Cooking",
        "title": "Session",
        "short_desc": "Will see how to cook different types of cooking",
        "created_at": "2022-12-06 17:22:38"
    },
    "error": null
}
```
### Request Workshop (update)
#### URL
```
/requestworkshop/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
    "category":"Cooking",
    "title":"Session 2", 
    "short_desc":"Will see how to cook different types of cooking"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "2",
        "category": "Cooking",
        "title": "Session 2",
        "short_desc": "Will see how to cook different types of cooking",
        "created_at": "2022-12-06 17:22:38"
    },
    "error": null
}
```
### Request Workshop (delete)
#### URL
```
/requestworkshop/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "response": "Record successfully deleted"
    }
}
```
### Request Workshop (list all)
#### URL
```
/requestworkshop/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "request_workshop": [
            {
                "id": "2",
                "category": "Cooking",
                "title": "Session 2",
                "short_desc": "Will see how to cook different types of cooking",
                "created_at": "2022-12-06 17:22:38"
            },
            {
                "id": "1",
                "category": "Banking",
                "title": "Session",
                "short_desc": "Will see how to fill passbook",
                "created_at": "2022-12-06 17:22:11"
            }
        ]
    },
    "error": null
}
```
### Shg Interest (create)
#### URL
```
/shgInterest/create
```
#### Type
```
post
```
#### Payload
```
{
    "amount": "1000",
    "interest_rate": "10",
    "shg_id": "10"
}
```
#### Response
```
{
    "status": 200,
    "message": "Record inserted succesfully",
    "error": null,
    "data": {
        "id": "5",
        "amount": "1000",
        "interest_rate": "10",
        "shg_id": "10",
        "created_at": "2022-12-07 18:18:19",
        "updated_at": "0000-00-00 00:00:00"
    }
}
```
### Shg Interest (update)
#### URL
```
/shgInterest/update/{id}
```
#### Type
```
patch
```
#### Response
```
{
    "status": 200,
    "message": "Record updated succesfully",
    "error": null,
    "data": {
        "id": "3",
        "amount": "30949",
        "interest_rate": "10",
        "shg_id": "10",
        "created_at": "2022-12-06 16:51:25",
        "updated_at": "0000-00-00 00:00:00"
    }
}
```
### Government Member Roles (create)
#### URL
```
governmentmemberroles/create
```
#### Type
```
post
```
#### Payload
```
{
    "role_name":"lead"  ,
    "access":{}
}
```
#### Response
```
{
    "status": 200,
    "message": "record added succesffully",
    "data": {
        "id": "2",
        "role_name": "lead",
        "access": "{}",
        "created_at": "2022-12-07 14:10:49"
    }
}
```
### Government Member Roles (read)
#### URL
```
governmentmemberroles/show/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": [
        {
            "id": "2",
            "role_name": "lead",
            "access": "{}",
            "created_at": "2022-12-07 14:10:49"
        }
    ],
    "error": null
}
```
### Government Member Roles (update)
#### URL
```
governmentmemberrole/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
    "role_name":"member"
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "1",
        "role_name": "member",
        "access": "{\"only lead\":true}",
        "created_at": "2022-12-07 14:05:17"
    },
    "error": null
}
```
### Government Member Roles (delete)
#### URL
```
governmentmemberroles/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "message": "record deleted succesfully",
    "error": null
}
```
### Government Member Roles (list all)
#### URL
```
governmentmemberroles/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "government_member_roles": [
            {
                "id": "1",
                "role_name": "teamlead",
                "access": "{\"only lead\":true}",
                "created_at": "2022-12-07 14:05:17"
            }
        ]
    },
    "error": null
}
```
### Internal Users Roles (create)
#### URL
```
internalusersroles/create
```
#### Type
```
post
```
#### Payload
```
{
    "role_name":"dp",
    "access":{}
}
```
#### Response
```
{
    "status": 200,
    "message": "record added successfully",
    "data": {
        "id": "4",
        "role_name": "dp",
        "access": "{}",
        "created_at": "0000-00-00 00:00:00"
    },
    "error": null
}
```
### Internal Users Roles (read)
#### URL
```
internalusersroles/show/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": [
        {
            "id": "1",
            "role_name": "lead",
            "access": "{\r\n\"access\":\"true\"\r\n}",
            "created_at": "2022-12-07 11:29:56"
        }
    ],
    "error": null
}
```
### Internal Users Roles (update)
#### URL
```
internalusersroles/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
    "role_name":"tech"  ,
    "access":{} 
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "2",
        "role_name": "tech",
        "access": "{}",
        "created_at": "2022-12-07 11:31:00"
    },
    "message": "record updated successfully",
    "error": null
}
```
### Internal Users Roles (delete)
#### URL
```
internalusersroles/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "message": "record deleted successfully",
    "error": null
}
```
### Internal Users Roles (list all)
#### URL
```
internalusersroles/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "internal_users_roles": [
            {
                "id": "2",
                "role_name": "member",
                "access": "{\r\n\"member access\":\"true\"\r\n}",
                "created_at": "2022-12-07 11:31:00"
            },
            {
                "id": "1",
                "role_name": "lead",
                "access": "{\r\n\"access\":\"true\"\r\n}",
                "created_at": "2022-12-07 11:29:56"
            }
        ]
    },
    "error": "null"
}
```
### Business Roles (create)
#### URL
```
businessroles/create/
```
#### Type
```
post
```
#### Payload
```
{
    "role_name":"boss",
    "access":{    
    }
}
```
#### Response
```
{
    "status": 200,
    "message": "record added successfully",
    "data": {
        "id": "6",
        "role_name": "boss",
        "access": "{}",
        "created_at": "2022-12-07 18:14:35"
    },
    "error": null
}
```
### Business Roles (read)
#### URL
```
businessroles/show/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": [
        {
            "id": "4",
            "role_name": "lead",
            "access": "{\"access\":false}\r\n",
            "created_at": "2022-12-07 18:02:57"
        }
    ],
    "error": null
}
```
### Business Roles (update)
#### URL
```
businessroles/update/{id}
```
#### Type
```
patch
```
#### Payload
```
{
    "role_name":"head",
    "access":{      
    }
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "6",
        "role_name": "head",
        "access": "{}",
        "created_at": "2022-12-07 18:14:35"
    },
    "message": "record updated successfully",
    "error": null
}
```
### Business Roles (delete)
#### URL
```
businessroles/delete
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "message": "record deleted successfully",
    "error": null
}
```
### Business Roles (list all)
#### URL
```
businessroles/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "business_roles": [
            {
                "id": "5",
                "role_name": "master",
                "access": "{\r\n\"access\":true\r\n}",
                "created_at": "2022-12-07 18:02:57"
            },
            {
                "id": "4",
                "role_name": "lead",
                "access": "{\"access\":false}\r\n",
                "created_at": "2022-12-07 18:02:57"
            },
            {
                "id": "1",
                "role_name": "member",
                "access": "{ \r\n\"access\":\"true\"\r\n}",
                "created_at": "2022-12-07 18:01:35"
            }
        ]
    },
    "error": null
}
```
### Applied Scheme (create)
#### URL
```
/appliedschemes/create
```
#### Type
```
post
```
#### Payload
```
{
    "shg_id": 3,
    "user_id": 126
}
```
#### Response
```
{
    "status": 204,
    "data": {
        "id": "8",
        "shg_id": "3",
        "user_id": "126",
        "created_at": "2022-12-07 18:00:22",
        "updated_at": "0000-00-00 00:00:00"
    },
    "message": null
}
```
### Applied Scheme (read)
#### URL
```
/appliedschemes/{id}
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "6",
        "shg_id": "1",
        "user_id": "123",
        "created_at": "2022-12-07 17:53:58",
        "updated_at": "0000-00-00 00:00:00"
    },
    "error": null
}
```
### Applied Scheme (update)
#### URL
```
/appliedschemes/update/{id}
```
#### Type
```
patch
```
#### Paylaod
```
{
    "user_id": 125
}
```
#### Response
```
{
    "status": 200,
    "data": {
        "id": "8",
        "shg_id": "3",
        "user_id": "125",
        "created_at": "2022-12-07 18:00:22",
        "updated_at": "0000-00-00 00:00:00"
    },
    "error": null
}
```
### Applied Scheme (delete)
#### URL
```
/appliedschemes/delete/{id}
```
#### Type
```
delete
```
#### Response
```
{
    "status": 200,
    "error": null,
    "messages": {
        "response": "Record deleted successfully"
    }
}
```
### Applied Scheme (list all)
#### URL
```
/appliedschemes/listAll
```
#### Type
```
get
```
#### Response
```
{
    "status": 200,
    "data": {
        "applied_scheme": [
            {
                "id": "8",
                "shg_id": "3",
                "user_id": "125",
                "created_at": "2022-12-07 18:00:22",
                "updated_at": "0000-00-00 00:00:00"
            },
            {
                "id": "7",
                "shg_id": "2",
                "user_id": "124",
                "created_at": "2022-12-07 17:54:41",
                "updated_at": "0000-00-00 00:00:00"
            }
        ]
    },
    "error": null
}
```
