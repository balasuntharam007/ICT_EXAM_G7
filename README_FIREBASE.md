# Grade 7 ICT Online Examination Portal
## இலங்கை தரம் 7 தகவல் மற்றும் தொடர்பாடல் தொழில்நுட்பப் பரீட்சை முறைமை

இந்த தளம் **Grade 7 (தரம் 7)** மாணவர்களுக்கானது. இது Cloud Firestore மற்றும் Firebase Authentication உடன் இணைந்து செயல்படும் வகையில் கட்டமைக்கப்பட்டுள்ளது.

---

### 1. இயல்புநிலை உள்நுழைவு விபரங்கள் (Default Credentials)

#### ஆசிரியர் / நிர்வாகி (Admin Login):
- **Email / Username:** `admin@ictg7.school` அல்லது `admin`
- **Password:** `Admin@2027`
- **பணிகள்:** மாணவர் கணக்குகளை நிர்வகித்தல், 100 மாணவர்களுக்கும் கடவுச்சொல் மாற்றுதல், 6 அலகுகளுக்கான மதிப்பெண்களைப் பார்வையிடல், Excel (.csv) வடிவில் முடிவுகளைப் பதிவிறக்குதல்.

#### 100 மாணவர் கணக்குகள் (100 Student Accounts):
- **Usernames:** `std001` முதல் `std100` வரை
- **Passwords:** `ict7@std001` முதல் `ict7@std100` வரை
- **உதாரணம்:**
  - மாணவர் 01: `std001` / கடவுச்சொல்: `ict7@std001`
  - மாணவர் 25: `std025` / கடவுச்சொல்: `ict7@std025`
  - மாணவர் 100: `std100` / கடவுச்சொல்: `ict7@std100`

---

### 2. பாட அலகுகள் (Curriculum Units)
1. **அலகு 1 – கணினியின் கூறுகளை இனங்காணல் (Identifying Parts of a Computer)**
2. **அலகு 2 – கோப்பு முகாமைத்துவம் (File Management)**
3. **அலகு 3 – சொல்முறைப்படுத்தல் (Word Processing)**
4. **அலகு 4 – இலத்திரனியல் விரிதாள் (Spreadsheets)**
5. **அலகு 5 – நிகழ்வுக் காட்சியளிப்பு (Presentations)**
6. **அலகு 6 – இணையமும் மின்னஞ்சலும் (Internet & Email)**

---

### 3. Firebase Cloud Firestore Collections
ஒரே Firebase திட்டத்தில் பிற வகுப்புகளுடன் மோதலின்றி தனித்துச் சேமிக்க பின்வரும் collections பயன்படுத்தப்படுகின்றன:
- மாணவர் விபரங்கள்: `students_g7`
- தேர்வு முடிவுகள்: `exam_results_g7`
- நிர்வாகி விபரங்கள்: `admins_g7`

---

### 4. இணையப் பயன்பாடு (How to Run)
`index.html` கோப்பை எந்தவொரு உலாவியிலும் (Google Chrome, MS Edge, Firefox) இரட்டைச் சொடுக்கு (Double-click) செய்து நேரடியாகப் பயன்படுத்தலாம். இணைய இணைப்பு இல்லாதபோதும் Local Cloud Simulation Mode இல் முழுமையாக இயங்கும்.
