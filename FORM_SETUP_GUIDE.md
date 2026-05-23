# 📧 Contact Form Setup Guide

Your contact form is now configured to send emails directly to your inbox!

## How It Works

When someone fills out the contact form on your website, you'll receive an email with:
- Their name
- Their email address
- Their phone number
- Selected art form
- Their message

---

## Setup Steps (One-Time Only)

### Step 1: Verify Your Email with Formspree

1. **Deploy your website first** (using GitHub Pages, Netlify, etc.)
2. **Visit your live website**
3. **Fill out the contact form** with test data
4. **Submit the form**

### Step 2: Check Your Email

1. Go to your email inbox
2. Look for an email from **Formspree** (check spam folder too!)
3. The email will say: "Confirm your email address"
4. **Click the confirmation link** in the email

### Step 3: Done! ✅

After confirmation, all future form submissions will be sent directly to your email!

---

## What Happens When Someone Submits the Form

1. **User fills out the form** on your website
2. **Clicks "Send Message"**
3. **Form data is sent** to Formspree
4. **You receive an email** at tejareddy2311@gmail.com
5. **User sees success message** on the website

---

## Email Format You'll Receive

```
From: Formspree <noreply@formspree.io>
To: your-email@gmail.com
Subject: New submission from your form

Name: John Doe
Email: john@example.com
Phone: 555-1234
Art Form: Watercolor Painting
Message: I'm interested in learning watercolor painting...
```

---

## Important Notes

### ✅ Advantages of Formspree:
- **100% FREE** for up to 50 submissions/month
- **No coding required** - already set up!
- **Spam protection** included
- **Email notifications** instant
- **Works immediately** after email confirmation

### 📊 Free Plan Limits:
- 50 submissions per month
- 1 form
- Email notifications
- Spam filtering

### 💰 If You Need More:
If you get more than 50 inquiries per month (great problem to have!):
- **Formspree Plus:** $10/month for 1,000 submissions
- Or switch to another service (see alternatives below)

---

## Testing Your Form

### Before Deploying:
The form won't work on your local computer (file:// URLs). You must deploy first.

### After Deploying:
1. Visit your live website
2. Go to the Contact section
3. Fill out the form with your own email
4. Submit
5. Check your email inbox for confirmation email
6. Click the confirmation link
7. Test again - you should receive the submission!

---

## Alternative Form Services (If Needed)

### Option 1: Netlify Forms (If using Netlify)
**Cost:** FREE (100 submissions/month)

Update your form in `index.html`:
```html
<form class="contact-form" name="contact" method="POST" data-netlify="true">
```

### Option 2: EmailJS
**Cost:** FREE (200 emails/month)

1. Sign up at [emailjs.com](https://emailjs.com)
2. Connect your Gmail account
3. Get your Service ID and Template ID
4. Update JavaScript with EmailJS code

### Option 3: Web3Forms
**Cost:** FREE (250 submissions/month)

1. Sign up at [web3forms.com](https://web3forms.com)
2. Get your Access Key
3. Update form action:
```html
<form action="https://api.web3forms.com/submit" method="POST">
    <input type="hidden" name="access_key" value="YOUR-ACCESS-KEY">
    <!-- rest of form -->
</form>
```

---

## Troubleshooting

### Problem: Not receiving emails
**Solutions:**
1. Check spam/junk folder
2. Make sure you clicked the confirmation link
3. Wait 5 minutes and try again
4. Check Formspree dashboard at formspree.io

### Problem: Form shows error
**Solutions:**
1. Make sure website is deployed (not running locally)
2. Check internet connection
3. Try different browser
4. Clear browser cache

### Problem: Confirmation email not received
**Solutions:**
1. Check spam folder
2. Wait 10 minutes
3. Try submitting form again
4. Check email address is correct: tejareddy2311@gmail.com

---

## Customizing Email Notifications

### Want to change the email format?
1. Log in to [formspree.io](https://formspree.io)
2. Go to your form settings
3. Customize email template
4. Add auto-reply to users
5. Set up multiple recipients

### Want to add auto-reply?
In Formspree dashboard:
1. Go to Form Settings
2. Enable "Auto-responder"
3. Customize the message sent to users
4. Save changes

---

## Security Features

✅ **Spam Protection:** Formspree includes built-in spam filtering
✅ **reCAPTCHA:** Can be enabled in Formspree settings
✅ **Email Validation:** Form requires valid email format
✅ **HTTPS:** All data transmitted securely

---

## Monitoring Form Submissions

### View All Submissions:
1. Go to [formspree.io](https://formspree.io)
2. Log in with your account
3. View submission history
4. Export data if needed

### Get Notifications:
- Email (default) ✅
- Slack (upgrade required)
- Webhook (upgrade required)

---

## Quick Reference

**Your Form Endpoint:** `https://formspree.io/f/xanyrgko`
**Monthly Limit:** 50 submissions (FREE)
**Setup Required:** Email confirmation (one-time)

---

## Next Steps

1. ✅ Form is already configured in your website
2. 📤 Deploy your website
3. 📧 Submit test form
4. ✉️ Confirm your email
5. 🎉 Start receiving inquiries!

---

## Support

- **Formspree Help:** https://help.formspree.io
- **Formspree Status:** https://status.formspree.io
- **Contact Formspree:** support@formspree.io

---

**Your contact form is ready to go! Just deploy your website and confirm your email.** 🚀

All form submissions will be sent directly to your email inbox!