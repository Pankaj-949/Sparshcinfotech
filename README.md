from pathlib import Path

# Content for README.md
readme_content = """# Sparsh Infotech – Complete IT Solutions

💻 Computer & Laptop AMC | 🌐 Networking | 🖨️ Printer Repair | 🎥 CCTV Setup | 💡 Electrical Work

---

## 📢 About Us
Sparsh Infotech is your trusted partner for IT and Electrical services.  
We provide reliable and affordable solutions for:  
- Computer & Laptop Repair / AMC (Annual Maintenance)  
- Networking & Internet Setup  
- Printer Repair, Cartridge Refill & Maintenance  
- CCTV Installation & Service  
- Home & Office Electrical Work  

---

## 💰 AMC Packages (Highlights)
- **Basic:** ₹1,500 / PC / Year (Remote + 2 onsite visits)  
- **Standard:** ₹3,000 / PC / Year (Quarterly check, minor hardware repair)  
- **Premium:** ₹5,500 / PC / Year (Next-day onsite, staff training, full coverage)  

👉 Lumpsum plans available for **Shops, Schools, Banks, Offices**.  

---

## 📞 Contact
**Pankaj Tambe**  
📱 95270 23124 / 93721 17669  
📧 [pankajtambe1221@gmail.com](mailto:pankajtambe1221@gmail.com)  
📍 Ratnagiri – Sangmeshwar  

---

👉 Visit our Website: https://<your-username>.github.io/sparshcomputersolution/
"""

# Save the file as README.md
file_path = Path("/mnt/data/README.md")
file_path.write_text(readme_content, encoding="utf-8")

file_path
