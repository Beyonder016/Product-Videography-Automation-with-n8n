# 🎞️ Product Videography Automation with n8n

**Automate the creation of professional marketing materials (photo & video) with just a form submission!**

---

## 🚀 **Project Overview**

This project uses **n8n**, **AI tools**, and **automation APIs** to transform simple product submissions into **studio-quality visuals** and **dynamic product videos** — all in one automated workflow.

With just a **product photo, title, description, and an email**, the system generates:

* 📸 **Hyper-realistic Product Image**
* 🎥 **3D Spinning Product Video**
* 📧 **Email Delivery of Assets**

---

## 📈 **Features**

* 🔧 **Form-based Trigger**
* 🚀 **Image Enhancement with AI (OpenAI Image API)**
* 🔍 **Image Hosting (ImageBB for Public URL)**
* 🎥 **Video Generation (Runway Gen-4 Turbo API)**
* ⌛ **Polling with Wait Mechanism (Smart Looping for Status Check)**
* 📂 **Google Drive Upload of Raw & Processed Assets**
* 📧 **Automated Email with Attachments & Links**

---

## 📚 **Tech Stack & Tools**

| Tool                   | Purpose                        |
| ---------------------- | ------------------------------ |
| **n8n**                | Automation Workflow Engine     |
| **OpenAI GPT-4.1**     | Dynamic Prompt Generation      |
| **OpenAI Image API**   | Photo Enhancement & Editing    |
| **ImageBB API**        | Public Image URL Hosting       |
| **Runway Gen-4 Turbo** | 3D Product Video Generation    |
| **Google Drive API**   | Raw & Processed File Storage   |
| **Gmail API**          | Email Delivery of Final Assets |

---

## 🔬 **Workflow Pipeline**

1. **Form Submission**

   * Upload product photo
   * Provide product name, description & email

2. **Image Processing**

   * AI prompt generation (product-focused)
   * Image editing & enhancement using OpenAI's Image API

3. **Public Hosting & Video Generation**

   * Upload image to ImageBB for URL
   * Pass URL to Runway API for 3D video creation

4. **Smart Polling & Status Checks**

   * n8n loop with dynamic wait conditions

5. **Delivery**

   * Email final image & video links
   * Store raw and edited assets on Google Drive

---

## 🎥 **Demo Video**

\[PLACEHOLDER FOR DEMO VIDEO LINK]

*Upload your demo video link here once available.*

---

## 🔍 **Example Use Case**

* D2C Brands generating marketing assets
* Creators automating product showcases
* Marketing teams scaling content creation
* Freelancers offering on-demand videography automation

---

## 🔧 **Setup Instructions**

1. Clone the repo (if applicable)
2. Import the **n8n workflow JSON** into your n8n instance
3. Configure API Keys:

   * OpenAI
   * Runway
   * ImageBB
   * Google Drive
   * Gmail
4. Adjust prompts in AI agents as needed
5. Deploy and run your automated videography pipeline!

---

## 🖊️ **Customization**

* 🌀 Modify prompts for different video effects (e.g., zoom, pan)
* 🌟 Use different models via OpenRouter integration
* 💡 Expand to social media auto-posting or CRM integrations

---

## 🌐 **License**

[MIT License](LICENSE)

---

## 🙋️ **Contributing**

Pull requests and ideas are welcome! Feel free to fork and adapt this workflow for creative use cases.

---

## 💬 **Credits & Acknowledgements**

Special thanks to the n8n community and the open-source ecosystem for making complex automation accessible.

---

**Let's automate creativity!**
