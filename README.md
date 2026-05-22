# PI Randomizer Tool

**A web-based tool for randomizing Plant Introduction (PI) numbers in plant breeding experiments**

---

## 📋 Overview

The **PI Randomizer** is a professional tool designed to help plant breeders and researchers randomize Plant Introduction (PI) accessions across multiple replications. This tool streamlines the experimental design process by generating randomized PI assignments with unique random values for statistical analysis.

**Developed at:** [Punnuris Lab](#contact) • Fort Valley State University (FVSU)

---

## ✨ Key Features

- ✅ **Two Replication Support** - Create Rep1 and Rep2 with different randomizations
- 🎲 **Random Value Generation** - Generate random numbers from 0 to 1 with configurable precision
- 📊 **Batch Processing** - Handle hundreds of plots efficiently
- 💾 **Excel Import/Export** - Work directly with .xlsx files
- 🔒 **Privacy First** - All processing happens locally (100% private, no data stored)
- ⚡ **Fast & Efficient** - Instant processing and download
- 📱 **Responsive Design** - Works on desktop and mobile devices
- 🎨 **Professional UI** - Beautiful, intuitive interface built with modern web standards

---

## 🚀 Quick Start

### **Option 1: Online (No Installation Required)**
1. Open `PI_Randomizer.html` in any web browser
2. Click to upload your Excel file
3. Configure your settings
4. Download the randomized results

### **Option 2: From GitHub**
Visit the GitHub repository and open `PI_Randomizer.html` directly in your browser.

---

## 📖 How to Use

### **Step 1: Prepare Your Data**
Create an Excel file (.xlsx) with:
- **Column A (Plot Column):** Plot numbers (e.g., 250016, 250017, etc.)
- **Column B (PI Column):** Plant Introduction numbers (e.g., PI12345, PI67890, etc.)
- **Additional Columns:** Any other data you want to keep (optional)

**Example:**
```
Plot      | PI       | Accession_Name | Other_Data
250016    | PI12345  | Variety A      | ...
250017    | PI67890  | Variety B      | ...
...
```

### **Step 2: Upload File**
- Click the upload section or drag & drop your Excel file
- The tool automatically detects available columns

### **Step 3: Configure Settings**
- **Plot Column:** Select which column contains plot numbers
- **PI Column:** Select which column contains PI numbers to randomize
- **Random Decimal Places:** Choose precision (2-5 decimal places)
- **Keep Other Columns:** Toggle to include/exclude additional columns

### **Step 4: Generate**
- Click **"Generate Randomized Files"**
- The tool creates two sheets: Rep1 and Rep2

### **Step 5: Download**
- Click **"Download Excel"** to save your randomized file
- Result file contains two sheets with different randomizations

---

## 📊 Output Format

The generated Excel file contains two worksheets:

### **Rep1 (First Replication)**
```
Plot      | PI       | Random_Value | [Other Columns]
250016    | PI67890  | 0.573        | ...
250017    | PI12345  | 0.891        | ...
...
```

### **Rep2 (Second Replication)**
```
Plot      | PI       | Random_Value | [Other Columns]
250016    | PI45678  | 0.234        | ...
250017    | PI23456  | 0.756        | ...
...
```

**Note:** Rep1 and Rep2 have different PI randomizations while maintaining the same plot structure.

---

## 🛠️ Technical Details

### **Technology Stack**
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Libraries:** 
  - [SheetJS (xlsx)](https://sheetjs.com/) - Excel file handling
  - No backend required (100% client-side processing)

### **Browser Compatibility**
- ✅ Chrome/Chromium (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile Browsers (iOS Safari, Chrome Mobile)

### **Performance**
- Files up to 10,000 rows process instantly
- All data processing happens on your device
- No data is sent to servers

---

## 📁 File Structure

```
pi-randomizer/
├── README.md                    # This file
├── PI_Randomizer.html          # Main application
└── LICENSE                      # License information
```

---

## 🔧 Installation & Hosting

### **Local Use**
Simply open `PI_Randomizer.html` in any web browser.

### **Host on GitHub Pages**
1. Create a GitHub repository
2. Upload `PI_Randomizer.html`
3. Enable GitHub Pages in Settings
4. Access via: `https://username.github.io/pi-randomizer/`

### **Host on Alternative Platforms**
The tool can be hosted on:
- **Netlify** - Drag & drop deployment
- **Vercel** - Automatic Git integration
- **Firebase Hosting** - Google's hosting platform
- **Any Web Server** - Just serve the HTML file

---

## 📋 Requirements

### **Input File Requirements**
- **Format:** Excel (.xlsx)
- **Minimum Columns:** 2 (Plot numbers, PI numbers)
- **Maximum Rows:** Tested up to 10,000 rows
- **Character Encoding:** UTF-8

### **System Requirements**
- **Modern Web Browser** (Chrome, Firefox, Safari, Edge)
- **No Special Software Needed** - Runs entirely in browser

---

## 🎯 Use Cases

### **Plant Breeding Experiments**
- Randomize germplasm accessions across field trials
- Create replicated experimental designs
- Generate random values for statistical analysis

### **Genetic Studies**
- Randomize plant introduction numbers for controlled experiments
- Maintain plot structure while changing PI assignments
- Support multi-replication study designs

### **Field Trials**
- Design large-scale field experiments
- Randomize accessions for multiple growing seasons
- Generate standardized data formats

---

## 🤝 Contributing

We welcome contributions! If you have suggestions or improvements:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit changes (`git commit -m 'Add amazing feature'`)
5. Push to branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

This means you can:
- ✅ Use commercially
- ✅ Modify the code
- ✅ Distribute the code
- ✅ Use privately

Just include the license notice!

---

## 🔒 Privacy & Security

- **No Data Collection** - Your files never leave your computer
- **No Tracking** - No analytics or tracking code
- **No Backend** - Entirely runs on your device
- **Open Source** - Code is transparent and auditable
- **Safe to Use** - Works completely offline

---

## ❓ FAQ

### **Q: Is my data safe?**
A: Yes! All processing happens on your device. Your data never leaves your computer or goes to any server.

### **Q: Can I use this offline?**
A: Yes! Download the HTML file and open it locally. It works completely without internet.

### **Q: What file formats do you support?**
A: Currently supports .xlsx (Excel) files. CSV support can be added upon request.

### **Q: How many rows can I randomize?**
A: Tested up to 10,000+ rows with instant processing. Should work fine with even larger datasets.

### **Q: Can I modify the source code?**
A: Yes! The code is open source and fully available for modification under the MIT License.

### **Q: Does this work on mobile?**
A: Yes! The interface is responsive and works on tablets and smartphones.

### **Q: Can I use this for non-plant breeding applications?**
A: Yes! The tool works for any randomization task with two factors (plots and treatments).

---

## 🐛 Troubleshooting

### **File Upload Not Working**
- Ensure your file is in .xlsx format
- Try a different browser
- Check browser console for error messages

### **Randomization Looks Same in Rep1 and Rep2**
- This is normal for the first few rows with small datasets
- Larger datasets will show more obvious differences
- Random values are always different

### **Downloaded File is Blank**
- Check if your source file has data
- Ensure at least 2 columns are present
- Try re-uploading the file

### **Browser Compatibility Issues**
- Update your browser to the latest version
- Try a different browser (Chrome, Firefox)
- Clear browser cache and reload

---

## 📞 Contact

**Punnuris Lab**  
Fort Valley State University (FVSU)  
Plant Breeding, Genetics & Crop Improvement

For questions, suggestions, or collaboration:
- 📧 Email: [Your Lab Email]
- 🌐 Website: https://fvsu.edu
- 📍 Location: Fort Valley, Georgia, USA

---

## 📚 References & Related Tools

- [Plant Introduction (PI) System - USDA GRIN](https://www.ars-grin.gov/)
- [R DesignR Package](https://cran.r-project.org/web/packages/desplot/) - For experimental designs
- [SheetJS Documentation](https://docs.sheetjs.com/)

---

## 🙏 Acknowledgments

This tool was developed to streamline the experimental design process for plant breeding research. Built with modern web technologies and designed with researchers in mind.

---

## 📈 Version History

### **Version 1.0** (2024)
- Initial release
- Support for two replications
- Random value generation (0-1)
- Excel file import/export
- Responsive web design

---

## 💡 Future Enhancements

Planned features for future releases:
- [ ] CSV file support
- [ ] Three+ replication support
- [ ] Custom randomization algorithms
- [ ] Batch processing
- [ ] Data validation reports
- [ ] Direct Google Sheets integration
- [ ] API for programmatic access

---

**Last Updated:** May 2024

---

**Happy Randomizing! 🎲**

For the latest version and updates, visit our GitHub repository.
