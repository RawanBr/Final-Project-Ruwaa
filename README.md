#  موقع رؤى

## وصف المشروع
منصة ذكية واستثمارية تجمع **الموهوبين والمستقلين** مع **الخبراء والمحترفين**  
لتبادل المعرفة وصقل المهارات، وذلك من خلال:

- طلب **تقييم نقدي بنّاء** بمقابل مادي (الاستشارة)
- إتاحة الفرصة للخبراء لنشر **محتوى تعليمي مفيد**
- تحقيق **أرباح من المشاهدات والتفاعل**

---

##  روابط مهمة
- **Figma (تصميم الواجهة)**  
  https://www.figma.com/design/pcEfy5Lcon2ICeGnMe6mqk/Untitled?node-id=0-1&t=3ZOtMcUHkNJ8HPHm-1

-  **Use Case Diagram**  
  https://drive.google.com/file/d/1KpmDM5EN1G7fldjiL_ijgNSLWAnx_-1K/view?usp=sharing
-  **Class Diagram**  
https://www.mermaidchart.com/app/projects/6d0bb644-7b8a-4e7e-8c97-7701b21579f9/diagrams/8948717c-0e80-4633-93a8-326f4de43cc7/share/invite/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJkb2N1bWVudElEIjoiODk0ODcxN2MtMGU4MC00NjMzLTkzYTgtMzI2ZjRkZTQzY2M3IiwiYWNjZXNzIjoiVmlldyIsImlhdCI6MTc2NzEyNjA2N30.tu8Z_ObjTpSicw9FV1slDJwgP0h9hFZmFJFY0YImRTM

-  **Postman API – Base Flow Documentation**  
https://documenter.getpostman.com/view/31393047/2sBXVbJZNk

-  **Presentaion**  
https://www.canva.com/design/DAG7YjxyTNo/OpqC8TO_he5w_xoKvDo0JA/edit?utm_content=DAG7YjxyTNo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

---


##  التقنيات المستخدمة
- **Java – Spring Boot**
- **Gmail API**
- **OpenAI API**
- **JWT Authentication**
- **AWS Servers**
- **Moyasar Payment Gateway**

---

---

## Model System(11)
- **User**
- **Customer**
- **Expert**
- **Post**
- **Card**
- **Category**
- **Attachment**
- **Chat**
- **Message**
- **Review**
- **Subscription**

---

##  أعضاء الفريق
- **روان بدر برناوي**
- **عمار يعقوب**
- **شهد محمد الجعيثن**




| Method | Endpoint | Person |
|--------|----------|--------|
| CRUD    | User | روان |
| CRUD    | Review | روان |
| CRUD    | Card | روان |
| CRUD    | Attachment | روان |
| GET    | /api/v1/ai/analyze-customer-skills/{customerId} | روان |
| GET    | /api/v1/experts/get-expert-by-category/{category} | روان |
| GET    | /api/v1/experts/get-high-rated-by-category/{category} | روان |
| PUT    | /api/v1/expert/discount/{discountPercentage}/{days} | روان |
| PUT    | /api/v1/reviews/accept-review/{reviewId} | روان |
| PUT    | /api/v1/reviews/reject-review/{review_id} | روان |
| PUT    | /api/v1/reviews/reject-all-reviews | روان |
| GET    | /api/v1/reviews/get-pending-review | روان |
| POST    | /api/v1/reviews/request/{expertId}/{workId} | روان |
| GET    | /api/v1/reviews/get-send-requests | روان |
| GET    | /api/v1/reviews/completed/post/{postId} | روان |
| POST   | /api/v1/reviews/request/{expertId}/{workId} | روان |
| API   | Moyasar Integration | روان |
| API   | OpenAI Integration | روان |
| TASK   | JUnit Testing | روان |
| TASK   | Use Case Diagram | روان |
