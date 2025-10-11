<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "9b03446058b4eed46928ae5e46325ea0",
  "translation_date": "2025-10-11T11:24:22+00:00",
  "source_file": "00-course-setup/README.md",
  "language_code": "ta"
}
-->
# பாடநெறி அமைப்பு

## அறிமுகம்

இந்த பாடத்தில், இந்த பாடநெறியின் குறியீட்டு மாதிரிகளை எவ்வாறு இயக்குவது என்பதை கற்றுக்கொள்வீர்கள்.

## மற்ற மாணவர்களுடன் இணைந்து உதவி பெறுங்கள்

உங்கள் ரெப்போவை கிளோன் செய்யும் முன், [AI Agents For Beginners Discord channel](https://aka.ms/ai-agents/discord) இல் இணைந்து அமைப்புக்கான உதவி, பாடநெறி தொடர்பான கேள்விகள் அல்லது மற்ற மாணவர்களுடன் தொடர்பு கொள்ளுங்கள்.

## இந்த ரெப்போவை கிளோன் செய்யவும் அல்லது ஃபார்க் செய்யவும்

தொடங்க, GitHub Repository ஐ கிளோன் செய்யவும் அல்லது ஃபார்க் செய்யவும். இது உங்கள் சொந்த பதிப்பை உருவாக்க உதவுகிறது, இதனால் நீங்கள் குறியீட்டை இயக்க, சோதிக்க மற்றும் மாற்ற முடியும்!

இதை செய்ய, <a href="https://github.com/microsoft/ai-agents-for-beginners/fork" target="_blank">ரெப்போவை ஃபார்க் செய்ய</a> லிங்க்கை கிளிக் செய்யவும்.

இப்போது, இந்த பாடநெறியின் ஃபார்க் செய்யப்பட்ட பதிப்பு உங்கள் கீழ்கண்ட லிங்க்கில் இருக்கும்:

![Forked Repo](../../../translated_images/forked-repo.33f27ca1901baa6a5e13ec3eb1f0ddd3a44d936d91cc8cfb19bfdb9688bd2c3d.ta.png)

## குறியீட்டை இயக்குதல்

இந்த பாடநெறி, AI Agents உருவாக்குவதற்கான அனுபவத்தை வழங்க Jupyter Notebooks தொடரை வழங்குகிறது.

குறியீட்டு மாதிரிகள் கீழ்கண்டவற்றை பயன்படுத்துகின்றன:

**GitHub கணக்கு தேவை - இலவசம்**:

1) Semantic Kernel Agent Framework + GitHub Models Marketplace. (semantic-kernel.ipynb) என லேபிள் செய்யப்பட்டுள்ளது.
2) AutoGen Framework + GitHub Models Marketplace. (autogen.ipynb) என லேபிள் செய்யப்பட்டுள்ளது.

**Azure சந்தா தேவை**:
3) Azure AI Foundry + Azure AI Agent Service. (azureaiagent.ipynb) என லேபிள் செய்யப்பட்டுள்ளது.

இந்த மூன்று வகையான உதாரணங்களை முயற்சிக்குமாறு உங்களை ஊக்குவிக்கிறோம், எது உங்களுக்கு சிறந்தது என்பதை கண்டறிய.

நீங்கள் எந்த விருப்பத்தை தேர்ந்தெடுக்கிறீர்கள் என்பதைப் பொறுத்து, கீழே உள்ள அமைப்பு படிகளை நீங்கள் பின்பற்ற வேண்டும்:

## தேவைகள்

- Python 3.12+
  - **NOTE**: Python3.12 நிறுவப்படவில்லை என்றால், அதை நிறுவவும். பின்னர் python3.12 ஐப் பயன்படுத்தி உங்கள் venv ஐ உருவாக்கவும், இதனால் requirements.txt கோப்பிலிருந்து சரியான பதிப்புகள் நிறுவப்படும்.
  
    >உதாரணம்

    Python venv கோப்பகத்தை உருவாக்கவும்:

    ``` bash
    python3 -m venv venv
    ```

    பின்னர் venv சூழலைச் செயல்படுத்தவும்:

    macOS மற்றும் Linux

    ```bash
    source venv/bin/activate
    ```
  
    Windows

    ```bash
    venv\Scripts\activate
    ```

- GitHub கணக்கு - GitHub Models Marketplace ஐ அணுக
- Azure சந்தா - Azure AI Foundry ஐ அணுக
- Azure AI Foundry கணக்கு - Azure AI Agent Service ஐ அணுக

இந்த ரெப்போசிட்டரியின் மூலத்தில் `requirements.txt` கோப்பை சேர்த்துள்ளோம், இது குறியீட்டு மாதிரிகளை இயக்க தேவையான Python தொகுதிகளை உள்ளடக்கியது.

கீழே உள்ள கட்டளையை உங்கள் டெர்மினலில் ரெப்போசிட்டரியின் மூலத்தில் இயக்குவதன் மூலம் அவற்றை நிறுவலாம்:

```bash
pip install -r requirements.txt
```
Python மெய்நிகர் சூழலை உருவாக்க பரிந்துரைக்கிறோம், இது எந்தவொரு முரண்பாடுகளையும் பிரச்சினைகளையும் தவிர்க்க உதவும்.

## VSCode அமைப்பு
VSCode இல் சரியான Python பதிப்பைப் பயன்படுத்துகிறீர்கள் என்பதை உறுதிப்படுத்தவும்.

![image](https://github.com/user-attachments/assets/a85e776c-2edb-4331-ae5b-6bfdfb98ee0e)

## GitHub Models பயன்படுத்தும் மாதிரிகளுக்கான அமைப்பு 

### படி 1: உங்கள் GitHub Personal Access Token (PAT) ஐ பெறுங்கள்

இந்த பாடநெறி GitHub Models Marketplace ஐ பயன்படுத்துகிறது, இது உங்களுக்கு AI Agents உருவாக்க பயன்படுத்தப்படும் பெரிய மொழி மாதிரிகளை (LLMs) இலவசமாக அணுக வழங்குகிறது.

GitHub Models ஐ பயன்படுத்த, நீங்கள் [GitHub Personal Access Token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) ஐ உருவாக்க வேண்டும்.

இதை உங்கள் GitHub கணக்கில் உள்ள <a href="https://github.com/settings/personal-access-tokens" target="_blank">Personal Access Tokens settings</a> இல் சென்று செய்யலாம்.

தயவுசெய்து [Principle of Least Privilege](https://docs.github.com/en/get-started/learning-to-code/storing-your-secrets-safely) ஐ பின்பற்றவும். இது உங்கள் டோக்கனுக்கு இந்த பாடநெறியில் குறியீட்டு மாதிரிகளை இயக்க தேவையான அனுமதிகளை மட்டுமே வழங்க வேண்டும் என்பதைக் குறிக்கிறது.

1. உங்கள் திரையின் இடது பக்கத்தில் **Developer settings** இல் `Fine-grained tokens` விருப்பத்தைத் தேர்ந்தெடுக்கவும்.
   ![](../../../translated_images/profile_developer_settings.410a859fe749c755c859d414294c5908e307222b2c61819c3203bbeed4470e25.ta.png)

    பின்னர் `Generate new token` ஐத் தேர்ந்தெடுக்கவும்.

    ![Generate Token](../../../translated_images/fga_new_token.1c1a234afe202ab37483944a291ee80c1868e1e78082fd6bd4180fea5d5a15b4.ta.png)

2. உங்கள் டோக்கனின் நோக்கத்தை பிரதிபலிக்கும் விளக்கமான பெயரை உள்ளிடவும், பின்னர் அதை எளிதாக அடையாளம் காணலாம்.


    🔐 டோக்கன் காலம் பரிந்துரை

    பரிந்துரைக்கப்பட்ட காலம்: 30 நாட்கள்  
    மேலும் பாதுகாப்பான நிலைப்பாட்டிற்காக, 7 நாட்கள் போன்ற குறுகிய காலத்தைத் தேர்ந்தெடுக்கலாம் 🛡️  
    இது ஒரு தனிப்பட்ட இலக்கை அமைக்கவும், உங்கள் கற்றல் வேகத்தை அதிகரிக்கவும் உதவுகிறது 🚀.

    ![Token Name and Expiration](../../../translated_images/token-name-expiry-date.a095fb0de63868640a4c82d6b1bbc92b482930a663917a5983a3c7cd1ef86b77.ta.png)

3. டோக்கனின் வரம்பை இந்த ரெப்போசிட்டரியின் ஃபார்க்கிற்கு மட்டுமே வரையறுக்கவும்.

    ![Limit scope to fork repository](../../../translated_images/token_repository_limit.924ade5e11d9d8bb6cd21293987e4579dea860e2ba66d607fb46e49524d53644.ta.png)

4. டோக்கனின் அனுமதிகளை வரையறுக்கவும்: **Permissions** கீழ், **Account** தாவலை கிளிக் செய்து, "+ Add permissions" பொத்தானை கிளிக் செய்யவும். ஒரு டிராப்டவுன் தோன்றும். **Models** ஐ தேடவும், அதற்கான பெட்டியைச் சரிபார்க்கவும்.
    ![Add Models Permission](../../../translated_images/add_models_permissions.c0c44ed8b40fc143dc87792da9097d715b7de938354e8f771d65416ecc7816b8.ta.png)

5. டோக்கனை உருவாக்குவதற்கு முன் தேவையான அனுமதிகளை சரிபார்க்கவும். ![Verify Permissions](../../../translated_images/verify_permissions.06bd9e43987a8b219f171bbcf519e45ababae35b844f5e9757e10afcb619b936.ta.png)

6. டோக்கனை உருவாக்குவதற்கு முன், அதை கடவுச்சொல் மேலாளர் வால்ட் போன்ற பாதுகாப்பான இடத்தில் சேமிக்க தயாராக இருப்பதை உறுதிப்படுத்தவும், ஏனெனில் நீங்கள் அதை மீண்டும் காண முடியாது. ![Store Token Securely](../../../translated_images/store_token_securely.08ee2274c6ad6caf3482f1cd1bad7ca3fdca1ce737bc485bfa6499c84297c789.ta.png)

நீங்கள் உருவாக்கிய புதிய டோக்கனை நகலெடுக்கவும். இப்போது இந்த பாடநெறியில் உள்ள `.env` கோப்பில் இதைச் சேர்க்க வேண்டும்.


### படி 2: உங்கள் `.env` கோப்பை உருவாக்கவும்

உங்கள் `.env` கோப்பை உருவாக்க, உங்கள் டெர்மினலில் கீழே உள்ள கட்டளையை இயக்கவும்.

```bash
cp .env.example .env
```

இது உதாரண கோப்பை நகலெடுத்து `.env` கோப்பை உங்கள் கோப்பகத்தில் உருவாக்கும், அதில் சூழல் மாறிகளுக்கான மதிப்புகளை நிரப்ப வேண்டும்.

உங்கள் டோக்கனை நகலெடுத்து, `.env` கோப்பை உங்கள் விருப்பமான உரை திருத்தியில் திறந்து, `GITHUB_TOKEN` புலத்தில் உங்கள் டோக்கனை ஒட்டவும்.
![GitHub Token Field](../../../translated_images/github_token_field.20491ed3224b5f4ab24d10ced7a68c4aba2948fe8999cfc8675edaa16f5e5681.ta.png)


இப்போது நீங்கள் இந்த பாடநெறியின் குறியீட்டு மாதிரிகளை இயக்க முடியும்.

## Azure AI Foundry மற்றும் Azure AI Agent Service பயன்படுத்தும் மாதிரிகளுக்கான அமைப்பு

### படி 1: உங்கள் Azure Project Endpoint ஐ பெறுங்கள்


Azure AI Foundry இல் ஹப் மற்றும் திட்டத்தை உருவாக்குவதற்கான படிகளை பின்பற்றவும்: [Hub resources overview](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/ai-resources)


உங்கள் திட்டத்தை உருவாக்கிய பிறகு, உங்கள் திட்டத்திற்கான இணைப்பு சரத்தை பெற வேண்டும்.

இது Azure AI Foundry போர்டலில் உங்கள் திட்டத்தின் **Overview** பக்கத்திற்கு சென்று செய்யலாம்.

![Project Connection String](../../../translated_images/project-endpoint.8cf04c9975bbfbf18f6447a599550edb052e52264fb7124d04a12e6175e330a5.ta.png)

### படி 2: உங்கள் `.env` கோப்பை உருவாக்கவும்

உங்கள் `.env` கோப்பை உருவாக்க, உங்கள் டெர்மினலில் கீழே உள்ள கட்டளையை இயக்கவும்.

```bash
cp .env.example .env
```

இது உதாரண கோப்பை நகலெடுத்து `.env` கோப்பை உங்கள் கோப்பகத்தில் உருவாக்கும், அதில் சூழல் மாறிகளுக்கான மதிப்புகளை நிரப்ப வேண்டும்.

உங்கள் டோக்கனை நகலெடுத்து, `.env` கோப்பை உங்கள் விருப்பமான உரை திருத்தியில் திறந்து, `PROJECT_ENDPOINT` புலத்தில் உங்கள் டோக்கனை ஒட்டவும்.

### படி 3: Azure இல் உள்நுழையவும்

பாதுகாப்பு சிறந்த நடைமுறையாக, Microsoft Entra ID உடன் Azure OpenAI இல் [keyless authentication](https://learn.microsoft.com/azure/developer/ai/keyless-connections?tabs=csharp%2Cazure-cli?WT.mc_id=academic-105485-koreyst) ஐ பயன்படுத்துவோம்.

அடுத்ததாக, ஒரு டெர்மினலை திறந்து `az login --use-device-code` ஐ இயக்கி உங்கள் Azure கணக்கில் உள்நுழையவும்.

உள்நுழைந்த பிறகு, டெர்மினலில் உங்கள் சந்தாவைத் தேர்ந்தெடுக்கவும்.


## கூடுதல் சூழல் மாறிகள் - Azure Search மற்றும் Azure OpenAI 

Agentic RAG பாடம் - பாடம் 5 - Azure Search மற்றும் Azure OpenAI ஐ பயன்படுத்தும் மாதிரிகளை உள்ளடக்கியது.

இந்த மாதிரிகளை இயக்க விரும்பினால், உங்கள் `.env` கோப்பில் கீழே உள்ள சூழல் மாறிகளைச் சேர்க்க வேண்டும்:

### Overview Page (Project)

- `AZURE_SUBSCRIPTION_ID` - **Overview** பக்கத்தில் **Project details** ஐ சரிபார்க்கவும்.

- `AZURE_AI_PROJECT_NAME` - உங்கள் திட்டத்தின் **Overview** பக்கத்தின் மேல் பார்க்கவும்.

- `AZURE_OPENAI_SERVICE` - **Overview** பக்கத்தில் **Azure OpenAI Service** க்கான **Included capabilities** தாவலில் இதைத் தேடவும்.

### Management Center

- `AZURE_OPENAI_RESOURCE_GROUP` - **Management Center** இல் **Overview** பக்கத்தில் **Project properties** க்கு செல்லவும்.

- `GLOBAL_LLM_SERVICE` - **Connected resources** கீழ், **Azure AI Services** இணைப்பு பெயரைத் தேடவும். பட்டியலில் இல்லை என்றால், உங்கள் resource group இல் AI Services resource name ஐ **Azure portal** இல் சரிபார்க்கவும்.

### Models + Endpoints Page

- `AZURE_OPENAI_EMBEDDING_DEPLOYMENT_NAME` - உங்கள் embedding மாதிரியைத் தேர்ந்தெடுக்கவும் (எ.கா., `text-embedding-ada-002`) மற்றும் மாதிரி விவரங்களில் **Deployment name** ஐ கவனிக்கவும்.

- `AZURE_OPENAI_CHAT_DEPLOYMENT_NAME` - உங்கள் chat மாதிரியைத் தேர்ந்தெடுக்கவும் (எ.கா., `gpt-4o-mini`) மற்றும் மாதிரி விவரங்களில் **Deployment name** ஐ கவனிக்கவும்.

### Azure Portal

- `AZURE_OPENAI_ENDPOINT` - **Azure AI services** ஐ தேடவும், அதை கிளிக் செய்யவும், பின்னர் **Resource Management**, **Keys and Endpoint** க்கு செல்லவும், "Azure OpenAI endpoints" வரை கீழே செல்லவும், "Language APIs" ஐ நகலெடுக்கவும்.

- `AZURE_OPENAI_API_KEY` - அதே திரையில், KEY 1 அல்லது KEY 2 ஐ நகலெடுக்கவும்.

- `AZURE_SEARCH_SERVICE_ENDPOINT` - உங்கள் **Azure AI Search** resource ஐ தேடவும், அதை கிளிக் செய்யவும், **Overview** ஐ பார்க்கவும்.

- `AZURE_SEARCH_API_KEY` - பின்னர் **Settings** மற்றும் **Keys** க்கு சென்று முதன்மை அல்லது இரண்டாம் நிலை நிர்வாக விசையை நகலெடுக்கவும்.

### External Webpage

- `AZURE_OPENAI_API_VERSION` - [API version lifecycle](https://learn.microsoft.com/en-us/azure/ai-services/openai/api-version-deprecation#latest-ga-api-release) பக்கத்தில் **Latest GA API release** ஐ பார்வையிடவும்.

### keyless authentication அமைக்கவும்

உங்கள் சான்றுகளை hardcode செய்யாமல், Azure OpenAI உடன் keyless connection ஐ பயன்படுத்துவோம். இதற்காக, `DefaultAzureCredential` ஐ இறக்குமதி செய்து, பின்னர் `DefaultAzureCredential` செயல்பாட்டை அழைத்து சான்றை பெறுவோம்.

```python
from azure.identity import DefaultAzureCredential, InteractiveBrowserCredential
```

## ஏதேனும் பிரச்சினை உள்ளதா?

இந்த அமைப்பை இயக்குவதில் ஏதேனும் பிரச்சினைகள் இருந்தால், எங்கள் <a href="https://discord.gg/kzRShWzttr" target="_blank">Azure AI Community Discord</a> இல் இணையுங்கள் அல்லது <a href="https://github.com/microsoft/ai-agents-for-beginners/issues?WT.mc_id=academic-105485-koreyst" target="_blank">ஒரு பிரச்சினையை உருவாக்கவும்</a>.

## அடுத்த பாடம்

இந்த பாடநெறிக்கான குறியீட்டை இயக்க நீங்கள் தயாராக உள்ளீர்கள். AI Agents உலகத்தை மேலும் கற்றுக்கொள்வதில் மகிழுங்கள்! 

[AI Agents மற்றும் Agent பயன்பாட்டு வழக்குகளுக்கான அறிமுகம்](../01-intro-to-ai-agents/README.md)

---

**குறிப்பு**:  
இந்த ஆவணம் [Co-op Translator](https://github.com/Azure/co-op-translator) என்ற AI மொழிபெயர்ப்பு சேவையை பயன்படுத்தி மொழிபெயர்க்கப்பட்டுள்ளது. எங்கள் தரத்தை உறுதிப்படுத்த முயற்சிப்பதுடன், தானியங்கி மொழிபெயர்ப்புகளில் பிழைகள் அல்லது தவறுகள் இருக்கக்கூடும் என்பதை கவனத்தில் கொள்ளவும். அதன் தாய்மொழியில் உள்ள மூல ஆவணம் அதிகாரப்பூர்வ ஆதாரமாக கருதப்பட வேண்டும். முக்கியமான தகவல்களுக்கு, தொழில்முறை மனித மொழிபெயர்ப்பு பரிந்துரைக்கப்படுகிறது. இந்த மொழிபெயர்ப்பைப் பயன்படுத்துவதால் ஏற்படும் எந்த தவறான புரிதல்கள் அல்லது தவறான விளக்கங்களுக்கு நாங்கள் பொறுப்பல்ல.