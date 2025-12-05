# Bharatvoice-seva
A voice agent which helps us to make and get services from the government withless effort
# 🇮🇳 Bharat VoiceSeva  
### **A Real-Time Phone Call Voice Agent for Government Services**  
Built using **Murf Falcon – the consistently fastest TTS API** and integrated with ASR + conversational AI.

---video link

## 🧠 Overview  
**Bharat VoiceSeva** is a voice-driven phone-call agent designed to make government services accessible to every citizen — including those who cannot use apps, websites, or navigate complex online forms.

Citizens simply **dial a phone number**, speak naturally, and the voice agent handles the request end-to-end using real-time ASR + Murf Falcon TTS for fast, natural responses.

This prototype is built for the **Murf Voice Agent Hackathon at Techfest, IIT Bombay**, fulfilling all required criteria:  
- Real-time voice conversation  
- ASR-to-text + conversational AI  
- Murf Falcon for speech generation  
- Secure environment variable handling  
- Complete GitHub + demo + LinkedIn submission

---

## 🎯 Problem We’re Solving  
Millions of Indians struggle with basic digital services because of:  
- Long queues at government offices  
- Travel cost & lost wages  
- Complex apps/websites  
- Document confusion  
- Limited digital literacy  
- Lack of unified service platforms  

**VoiceSeva removes all barriers** by enabling *voice-only* access through a simple phone call — no internet, no smartphone literacy required.

---

## 🧠 Use Cases  
The agent currently supports **four key government + citizen services**, entirely through voice:

### **1️⃣ Temple Ticket Booking (Darshan / Seva Scheduling)**  
- Book temple entry slots, special darshan, or seva tickets  
- Instant confirmation via SMS  
- Ideal for elderly citizens & rural areas

### **2️⃣ Submit Complaints to Panchayat / Local Offices**  
- Road issues, drainage, electricity problems  
- Complaint auto-routed to relevant officer  
- Citizen receives ticket ID + follow-up updates

### **3️⃣ Climate & Weather Forecasts (Hyperlocal)**  
- Village-level 24-hour and 7-day forecasts  
- Rain alerts, heatwave warnings  
- Agriculture-friendly summaries

### **4️⃣ Apply for Certificates & Government Documents**  
Through voice only, citizens can request:  
- Birth Certificate  
- Caste Certificate  
- Income Certificate  
- Residence Certificate  
- Ration card updates  
- Any govt-issued document requiring basic information

The agent collects essential details conversationally and sends them securely to the appropriate service workflow.

---

## 🔧 Tech Stack  
- **ASR:** Whisper / AssemblyAI (speech → text)  
- **TTS:** Murf Falcon Streaming API (text → real-time voice)  
- **AI Orchestration:** n8n + LLM prompt flows  
- **Call Handling:** Twilio Phone Agent (inbound/outbound conversational voice)  
- **Database:** Google Sheets (logging) / optional Airtable  
- **Backend:** Node.js / Python microservice (optional)  
- **Deployment:** Local + cloud-ready architecture
