# 🌐 Build a Smart Cloud Application with Vibe Coding: Challenge Lab || GSP532 🚀 [![Open Lab](https://img.shields.io/badge/Open-Lab-blue?style=flat)](https://www.skills.google/course_templates/1459/labs/597230) [![Star the Repo](https://img.shields.io/github/stars/Smithaker10/Arcade-Google-Cloud-Labs?style=social)](https://github.com/Smithaker10/Arcade-Google-Cloud-Labs)

## ⚠️ Disclaimer ⚠️

<blockquote style="background-color: #fffbea; border-left: 6px solid #f7c948; padding: 1em; font-size: 15px; line-height: 1.5;">
  <strong>Educational Purpose Only:</strong> This script and guide are provided for the educational purposes to help you understand the lab services and boost your career. Before using the script, please open and review it to familiarize yourself with Google Cloud services.
  <br><br>
  <strong>Terms Compliance:</strong> Always ensure compliance with Qwiklabs' terms of service and YouTube's community guidelines. The aim is to enhance your learning experience — not to circumvent it.
</blockquote>

---

<div style="padding: 15px; margin: 10px 0;">

## ☁️ Run in Cloud Shell:
### Abhi kuch log ye tutorial dekhne ke baad video post karege or bolege 1st video on youtube 😏
```bash
gcloud services enable \
aiplatform.googleapis.com \
artifactregistry.googleapis.com \
compute.googleapis.com \
cloudbuild.googleapis.com \
run.googleapis.com
```

```bash
read -p $'\e[1;36mEnter your student email address (the one used to start the lab): \e[0m' STUDENT_EMAIL
PROJECT_ID=$(gcloud config get-value project)
echo -e "\n\e[1;34m Using Project ID:\e[0m \e[1;33m$PROJECT_ID\e[0m"
echo -e "\e[1;34m Using Student Email:\e[0m \e[1;33m$STUDENT_EMAIL\e[0m\n"
echo -e "\e[1;35mGranting Cloud Run Admin role...\e[0m"

gcloud projects add-iam-policy-binding "$PROJECT_ID" \
  --member="user:$STUDENT_EMAIL" \
  --role="roles/run.admin" \
  --quiet
echo -e "\e[1;35mGranting Vertex AI User role...\e[0m"
gcloud projects add-iam-policy-binding "$PROJECT_ID" \
  --member="user:$STUDENT_EMAIL" \
  --role="roles/aiplatform.user" \
  --quiet

echo -e "\n\e[1;32mIAM roles applied successfully for\e[0m \e[1;33m$STUDENT_EMAIL\e[0m \e[1;32mon project\e[0m \e[1;33m$PROJECT_ID\e[0m\n"
```
```bash
tools = [google_search]
```


</div>

---

## 🎉 **Congratulations! Lab Completed Successfully!** 🏆

---

## 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/smit-thaker-8681ab290/)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)]()
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/thaker_smit_29/)
![Telegram](https://img.shields.io/badge/-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)
![Discord](https://img.shields.io/badge/-Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)
[![Gmail](https://img.shields.io/badge/-Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/u/3/#inbox)
