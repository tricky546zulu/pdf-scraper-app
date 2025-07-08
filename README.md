# 🤖 Automated PDF Scraper

A mobile-friendly web app that automatically scrapes websites for PDFs, extracts text using AI OCR, and saves results to Airtable.

## 🚀 Live Demo

Visit: `https://yourusername.github.io/pdf-scraper-app`
*(Replace with your actual GitHub username)*

## ✨ Features

- 📱 **Mobile-Optimized**: Works perfectly on phones and tablets
- 🤖 **AI-Powered OCR**: Uses Mistral OCR for text extraction
- 🔄 **Automated Monitoring**: Continuously checks websites for new PDFs
- 📊 **Airtable Integration**: Automatically saves results to your database
- ⚙️ **Flexible Scheduling**: Hourly, daily, or weekly automation
- 🌐 **No Installation**: Runs directly in your browser

## 🎯 Perfect For

- Academic research paper collection
- Legal document monitoring
- Business report automation
- News and publication tracking
- Compliance document processing

## 🔧 Setup Instructions

### 1. Fork This Repository

1. Click “Fork” in the top right
1. Go to your forked repo settings
1. Enable GitHub Pages (Settings → Pages → Deploy from branch → main)

### 2. Configure Your Services

**Mistral OCR Setup:**

- Use your existing Hugging Face space: `https://sean546-mistral-ocr.hf.space`

**Airtable Setup:**

1. Create a new Airtable base
1. Create a table called “PDFs” with these fields:
- `PDF URL` (Single line text)
- `Title` (Single line text)
- `Extracted Text` (Long text)
- `Success` (Checkbox)
- `Error` (Single line text)
- `Source URL` (Single line text)
- `Job Name` (Single line text)
- `Processed At` (Date)
1. Get your API credentials:
- Go to https://airtable.com/account
- Generate a personal access token
- Find your base ID in the URL (starts with “app…”)

### 3. Configure the App

1. Open your live app URL
1. Tap the ⚙️ settings icon
1. Enter your Mistral OCR space URL
1. Add your Airtable credentials
1. Save settings

### 4. Create Automation Jobs

1. Tap “➕ Add” to create a new job
1. Name your job (e.g., “Research Papers”)
1. Add website URLs to monitor
1. Choose schedule (hourly/daily/weekly)
1. Save and enable

### 5. Start Automation

- Tap the ▶️ play button
- The app will now automatically:
  - Check websites for new PDFs
  - Extract text using OCR
  - Save results to Airtable

## 📱 Usage

### Creating Jobs

```
Job Name: "University Research"
URLs: 
  - https://university.edu/research/publications
  - https://department.edu/papers
Schedule: Daily
```

### Monitoring Results

- View recent extractions in the app
- Check your Airtable base for complete data
- Export results to Excel/CSV from Airtable

## 🔒 Privacy & Security

- All processing happens in your browser
- API keys stored locally only
- No data sent to third parties
- Open source and transparent

## 🛠 Customization

Edit the `index.html` file to:

- Change styling and colors
- Modify automation intervals
- Add new features
- Integrate with other services

## 📊 Monitoring

Track your automation:

- Real-time status in the app
- Job success/failure rates
- PDF processing statistics
- Airtable integration status

## 🆘 Troubleshooting

**App Won’t Load:**

- Check GitHub Pages is enabled
- Wait 5-10 minutes for deployment
- Ensure `index.html` is in root folder

**OCR Not Working:**

- Verify Mistral OCR space URL
- Check space is running and accessible
- Try with a simple PDF first

**Airtable Errors:**

- Verify API key and base ID
- Check table name matches exactly
- Ensure all required fields exist

## 🔄 Updates

To update your app:

1. Edit files directly in GitHub
1. Commit changes
1. Updates go live in 1-2 minutes

## 📞 Support

- Check the [Issues](../../issues) tab for common problems
- Create a new issue for bugs or feature requests
- Fork and contribute improvements

## 📄 License

MIT License - feel free to use, modify, and distribute!

-----

**Made with ❤️ for automated PDF processing**
