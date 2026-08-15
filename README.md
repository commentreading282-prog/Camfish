## 📥 Installation on Termux

Open Termux and run these commands **one by one**:

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

### 5. Give permission to installer

```bash
chmod +x install.sh
```

### 6. Run installer

```bash
./install.sh
```

### ▶️ Start the tool

After installation:

```bash
cd ~/Camfish
./camfish.sh
```
### Step 3 — Option Select Karein

Tool में कुछ options दिखाई देंगे। अपने **authorized/local test** के लिए कोई option select करें।

### Step 4 — Local Test Server

Tool एक local testing URL दिखा सकता है, उदाहरण के लिए:

```text
http://localhost:5225
```

इस URL को केवल अपने device या ऐसे test environment में खोलें जिसकी आपको अनुमति है।

### Step 5 — Camera Permission

अगर browser camera permission माँगे, तो केवल अपने authorized test device पर permission दें।

### Step 6 — Test Complete Karein

Test पूरा होने के बाद local server बंद करने के लिए:

```text
Ctrl + C
```
दबाएँ।

अगर test के दौरान images **तुम्हारे अपने authorized device** पर बनाई गई हैं, तो उन्हें Pictures folder में copy करने के लिए:

```bash
cp *.png ~/storage/shared/pictures/
```

इसके बाद अपने device में **Pictures** folder खोलें और test के दौरान बनाई गई images देखें।
