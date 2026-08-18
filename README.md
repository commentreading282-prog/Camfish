## 📥 Installation on Termux

Open **Termux** and run these commands **one by one**:

### 1. Update Termux

```bash
pkg update -y
```

### 2. Install Git

```bash
pkg install git -y
```

### 3. Download the repository

```bash
git clone https://github.com/commentreading282-prog/Camfish.git
```

### 4. Enter the folder

```bash
cd Camfish
```

### 5. Give permission to the tool

```bash
chmod +x camfish.sh
```

### ▶️ Start Camfish

```bash
./camfish.sh
```

If the above command doesn't work:

```bash
bash camfish.sh
```

---

## 🛠️ Using the Tool

### Step 1 — Start the Tool

Run:

```bash
cd ~/Camfish
./camfish.sh
```

### Step 2 — Option Select Karein

Tool में दिखाई देने वाले options में से अपने **authorized/local test** के लिए appropriate option select करें।

### Step 3 — Follow the Instructions

Tool द्वारा दिए गए instructions को ध्यान से follow करें और केवल अपने device या authorized test environment पर इसका उपयोग करें।

### Step 4 — Local Test

अगर tool local testing के लिए कोई URL दिखाता है, जैसे:

```text
http://localhost:5225
```

तो इसे केवल अपने device या authorized test environment में खोलें।

### Step 5 — Camera Permission

अगर browser camera permission माँगे, तो केवल **अपने authorized test device** पर permission दें।

### Step 6 — Test Complete

Test पूरा होने के बाद tool को बंद करने के लिए:

```text
Ctrl + C
```

दबाएँ।

### 📁 Test Files

अगर test के दौरान images तुम्हारे अपने authorized device पर बनाई गई हैं, तो उन्हें Pictures folder में copy करने के लिए:

```bash
cp *.png ~/storage/shared/pictures/
```

फिर अपने Android device में:

**Pictures → अपनी test images**

खोलकर images देख सकते हैं।

---

## 🔄 Update Camfish

पुराना version update करने के लिए:

```bash
cd ~/Camfish
git pull
chmod +x camfish.sh
./camfish.sh
```

---

## ⚠️ Disclaimer

🔐 **Educational & Authorized Use Only**

इस tool का उपयोग केवल अपने device, अपने test environment या ऐसे systems पर करें जहाँ आपके पास स्पष्ट permission हो।

🚫 Unauthorized access, surveillance, phishing या किसी अन्य illegal activity के लिए इसका उपयोग न करें।

👤 Tool का उपयोग करने की पूरी responsibility user की है।

---

## ⭐ Support

अगर आपको project useful लगे:

⭐ Star the repository
🍴 Fork the repository
🐛 Report issues
💡 Suggest improvements

### 🐟 Camfish

**Learn • Test • Build • Secure** 🔐
