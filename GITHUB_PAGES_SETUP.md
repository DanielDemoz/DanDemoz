# GitHub Pages Setup Guide

## Enable Interactive HTML Demos for Your Projects

Each of your projects now includes a beautiful, interactive HTML page that showcases results for non-technical audiences. Here's how to host them on GitHub Pages.

---

## What is GitHub Pages?

GitHub Pages is a free hosting service that turns HTML files in your repository into live websites. Perfect for:
- Portfolio demonstrations
- Non-technical presentations
- Stakeholder reports
- Interactive dashboards

---

## Setup Instructions

### Project 1: Toronto Transit Sentiment NLP

**File:** `toronto-transit-sentiment-nlp/index.html`

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select `main` branch
5. Under **Folder**, select `/ (root)`
6. Click **Save**
7. Your page will be live at: `https://danieldemoz.github.io/toronto-transit-sentiment-nlp/`

**Alternative: Use `docs/` folder**
- Create folder: `docs/`
- Move `index.html` to `docs/index.html`
- In GitHub Pages settings, select `docs` folder instead of root

---

### Project 2: Interactive Transit Dashboard

**File:** `interactive-transit-dashboard/index.html`

Follow same steps as above. Live at:
`https://danieldemoz.github.io/interactive-transit-dashboard/`

---

### Project 3: SQL Portfolio

**File:** `sql-portfolio/index.html`

Follow same steps as above. Live at:
`https://danieldemoz.github.io/sql-portfolio/`

---

## Update Your READMEs

After enabling GitHub Pages, add these badges and links to your README.md files:

### For NLP Project README
```markdown
## Live Demo

**View Interactive Results:** [https://danieldemoz.github.io/toronto-transit-sentiment-nlp/](https://danieldemoz.github.io/toronto-transit-sentiment-nlp/)

![Demo](https://img.shields.io/badge/Demo-Live-brightgreen)
```

### For Dashboard README
```markdown
## Live Demo

**View Interactive Dashboard:** [https://danieldemoz.github.io/interactive-transit-dashboard/](https://danieldemoz.github.io/interactive-transit-dashboard/)

![Demo](https://img.shields.io/badge/Demo-Live-brightgreen)
```

### For SQL Portfolio README
```markdown
## Live Examples

**View Interactive Examples:** [https://danieldemoz.github.io/sql-portfolio/](https://danieldemoz.github.io/sql-portfolio/)

![Demo](https://img.shields.io/badge/Demo-Live-brightgreen)
```

---

## Verify It Works

After enabling GitHub Pages:
1. Wait 2-3 minutes for deployment
2. Visit your page URL
3. Check that all interactive features work
4. Test on mobile devices

---

## Features of Your HTML Pages

### NLP Sentiment Analysis Page
- Interactive Plotly charts showing sentiment distribution
- Topic analysis with keywords
- Business recommendations
- Fully responsive design
- Professional styling

### Interactive Dashboard Page
- Multiple interactive visualizations
- KPI cards with metrics
- Performance trends
- Route comparisons
- Executive summary

### SQL Portfolio Page
- Tabbed interface for different analyses
- Sample query results displayed as tables
- Business insights for each query
- Non-technical explanations
- Skills showcase

---

## Customization Tips

### Change Colors
Edit the CSS in each `index.html` file:
```css
/* Find this section in <style> tags */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Update Data
The charts use JavaScript at the bottom of each HTML file. Update the data arrays to show your actual results.

### Add More Charts
Use Plotly documentation: https://plotly.com/javascript/

---

## Share Your Work

Once live, share your GitHub Pages links on:
- LinkedIn posts
- Resume/CV
- Email signatures
- Portfolio website
- Job applications

Example LinkedIn post:
```
Excited to share my latest project: Toronto Transit Sentiment Analysis using NLP!

🔍 Analyzed thousands of customer feedback messages
🤖 Used BERT AI model with 88.7% accuracy
📊 Identified key improvement areas

Check out the interactive results: https://danieldemoz.github.io/toronto-transit-sentiment-nlp/

#DataScience #MachineLearning #NLP #Analytics
```

---

## Troubleshooting

**Page not loading?**
- Check that `index.html` is in the correct folder
- Verify GitHub Pages is enabled in Settings
- Wait a few minutes after enabling

**Charts not showing?**
- Make sure you have internet connection (Plotly loads from CDN)
- Check browser console for errors (F12)

**Mobile issues?**
- All pages are responsive, but test on actual devices
- Adjust CSS media queries if needed

---

## Benefits of This Approach

✅ **Non-technical audience friendly** - Beautiful visuals, no code  
✅ **Free hosting** - GitHub Pages is completely free  
✅ **Easy to share** - Just send a URL link  
✅ **Professional presentation** - Looks like a production app  
✅ **Always accessible** - No need to run Python/SQL  
✅ **Portfolio piece** - Demonstrates full-stack skills  

---

## Next Steps

1. Enable GitHub Pages for all three projects
2. Test all URLs to ensure they work
3. Update README files with live demo links
4. Share on LinkedIn and professional networks
5. Add URLs to your resume

---

**Questions?** Each project folder contains the `index.html` file ready to deploy!

