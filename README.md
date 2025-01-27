The system to include **two mobile apps** (one for **service users**, one for **caregivers**) and a **website-based admin dashboard**. Below is breakdown of the scope, features, and workflows.

---

### **System Overview**
1. **Website** (Admin Dashboard):
   - Used by admins to manage users, approve bookings, and communicate with caregivers/service users.
   - No app needed for admins.

2. **Service User App**:
   - For service users (e.g., elders or families) to book caregivers, view bookings, and chat with caregivers **after admin approval**.

3. **Caregiver App**:
   - For caregivers to manage bookings, chat with service users **after approval**, and communicate with Carepass (admin team).

---

### **Key Features**

#### **1. Service User App**  
- **Registration/Login**:  
  - Users must register and complete eligibility checks **via the website first** (no registration in the app).  
- **Booking Management**:  
  - View/administer current and past bookings.  
- **Chat with Caregivers**:  
  - Chat with caregivers **only after a booking is approved by the admin**.  
- **Knowledge Section**:  
  - Access articles, guides, and FAQs.  
- **Notifications**:  
  - Receive updates about bookings, messages, and approvals.  
- **Caregiver Profiles**:  
  - View profiles of matched caregivers (skills, reviews, availability).  

---

#### **2. Caregiver App**  
- **Registration/Login**:  
  - Caregivers register **via the website** and are approved by the admin.  
- **Booking Management**:  
  - View upcoming/past bookings and schedules.  
- **Chat Features**:  
  - **Tab 1**: Chat with Carepass (admin team) for support or inquiries.  
  - **Tab 2**: Chat with service users **only after a booking is approved**.  
- **Knowledge Section**:  
  - Access training materials, policies, and FAQs.  
- **Notifications**:  
  - Alerts for new bookings, messages, or schedule changes.  
- **Profile Management**:  
  - Update availability, skills, and personal details.  

---

#### **3. Admin Dashboard (Website)**  
- **User Management**:  
  - Approve/reject caregivers and service users.  
- **Booking Approval**:  
  - Review and approve bookings before caregivers and users can communicate.  
- **Chat with All Parties**:  
  - Communicate with caregivers and service users directly via the dashboard.  
- **Knowledge Section Management**:  
  - Upload/edit articles and guides for both apps.  
- **Reporting**:  
  - Track bookings, user activity, and caregiver performance.  

---

### **Communication Rules**  
1. **Caregiver ↔ Service User**:  
   - Allowed **only after the admin approves a booking**.  
   - Chat is tied to the specific booking.  
2. **Caregiver ↔ Carepass (Admin)**:  
   - Allowed **at any time** via the caregiver app.  
3. **Service User ↔ Carepass (Admin)**:  
   - Allowed **at any time** via the service user app.  
4. **Group Chats**:  
   - Admins can create group chats (e.g., caregiver + user + admin) for coordination.  

---

### **Simplified Process Flow**  

#### **For Service Users**  
1. **Register and complete eligibility checks** on the website.  
2. **Submit application** with preferences (via website).  
3. **Admin matches caregivers** and approves the booking.  
4. **Use the app** to:  
   - Book approved caregivers.  
   - Chat with caregivers **after approval**.  
   - View booking history and caregiver profiles.  

---

#### **For Caregivers**  
1. **Register and get approved** via the website.  
2. **Use the app** to:  
   - View/manage bookings and schedules.  
   - Chat with Carepass (admin) **anytime**.  
   - Chat with service users **only after booking approval**.  
   - Access training materials in the Knowledge Section.  

---

#### **For Admins**  
1. **Manage users** (approve/reject caregivers and service users).  
2. **Review and approve bookings** to enable caregiver-user communication.  
3. **Monitor chats** between caregivers and users via the dashboard.  
4. **Update Knowledge Section** content for both apps.  

---

### **User Stories**  

#### **Service User Stories**  
1. “I want to book a caregiver approved by the admin and chat with them securely.”  
2. “I need to see my upcoming bookings and message Carepass for support.”  
3. “I want to read guides about care in the Knowledge Section.”  

#### **Caregiver Stories**  
1. “I want to view my schedule and chat with users only after bookings are approved.”  
2. “I need to contact Carepass (admin) for urgent help via the app.”  
3. “I want to update my availability and access training materials.”  

#### **Admin Stories**  
1. “I need to approve bookings before users and caregivers can communicate.”  
2. “I want to monitor all chats to ensure compliance and safety.”  
3. “I need to update the Knowledge Section with new policies.”  

---

### **Key Features Summary**  
| **Component**       | **Features**                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| **Service User App** | Booking management, caregiver profiles, chat (post-approval), Knowledge Section. |
| **Caregiver App**    | Schedule management, chat with Carepass/users (post-approval), Knowledge Section. |
| **Admin Dashboard**  | User/booking approval, chat with all parties, Knowledge Section management. |

---
