# 🌐 Assign External IP to VM Instance using gcloud 🚀 [![Open Lab](https://img.shields.io/badge/Open-Lab-blue?style=flat)](https://www.skills.google/games/7008/labs/43561) [![Star the Repo](https://img.shields.io/github/stars/Smithaker10/Arcade-Google-Cloud-Labs?style=social)](https://github.com/Smithaker10/Arcade-Google-Cloud-Labs)

## ⚠️ Disclaimer ⚠️

<blockquote style="background-color: #fffbea; border-left: 6px solid #f7c948; padding: 1em; font-size: 15px; line-height: 1.5;">
  <strong>Educational Purpose Only:</strong> This script and guide are provided for the educational purposes to help you understand the lab services and boost your career.Before using the script, please open and review it to familiarize yourself with Google Cloud services.
  <br><br>
  <strong>Terms Compliance:</strong> Always ensure compliance with Qwiklabs' terms of service and YouTube's community guidelines. The aim is to enhance your learningexperience — not to circumvent it.
</blockquote>

---

<div style="padding: 15px; margin: 10px 0;">

## ☁️ Run in Cloud Shell:
## Paste and Hit Enter Nothing to Change
```bash
export VM_NAME=$(gcloud compute instances list --format='value(name)' --limit=1) && export ZONE=$(gcloud compute instances list --format='value(zone)' --limit=1) && export REGION=${ZONE%-*}
gcloud compute addresses create lab-static-ip --region=$REGION
export IP_ADDRESS=$(gcloud compute addresses describe lab-static-ip --region=$REGION --format='get(address)') && gcloud compute instances add-access-config $VM_NAME --zone=$ZONE --address=$IP_ADDRESS
## Iska bhi Credit chahiye kya?😂
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
