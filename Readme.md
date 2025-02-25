# 🎸 Band Name Generator 🎶  

This is a simple **Band Name Generator** written in Python. It asks the user for their **city** and **pet's name**, then combines them to generate a unique band name!  

## 🚀 How It Works  
1. The program welcomes the user.  
2. It asks for the **city** the user lives in.  
3. It then asks for the **pet's name**.  
4. Finally, it combines both inputs and suggests a **band name**.  

## 🖥️ Example Usage  
```bash
Welcome to the Band Name Generator  
What city are you in? New York  
What is your pet? Luna  
Your band name could be New York Luna  
```

## ▶️ Running the Program  
1. Make sure you have **Python installed**.  
2. Run the script using:  
   ```bash
   python Band-Name-Generator.py
   ```

## 📌 Code  
```python
print("Welcome to the Band Name Generator")

city = input("What city are you in? ")
pet = input("What is your pet? ")

print("Your band name could be " + city + " " + pet)
```
