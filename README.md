# PDF summarizer for Alfred
![GitHub Downloads](https://img.shields.io/github/downloads/chrisgrieser/pdf-summarizer-alfred/total?label=GitHub%20Downloads&style=plastic&logo=github)
![Alfred Gallery Downloads](https://img.shields.io/badge/dynamic/yaml?url=https%3A%2F%2Fraw.githubusercontent.com%2Fchrisgrieser%2F.config%2Frefs%2Fheads%2Fmain%2FAlfred.alfredpreferences%2Falfred-gallery-downloads.yaml&query=pdf-summarizer&style=plastic&logo=alfred&label=Gallery%20Downloads&color=%235C1F87)
![Latest Release](https://img.shields.io/github/v/release/chrisgrieser/pdf-summarizer-alfred?label=Latest%20Release&style=plastic)

Get summaries of your PDFs via [ChatPDF](https://www.chatpdf.com/) with just one
hotkey.

Requires a ChatPDF API key, which is (currently) free for 5000 PDF pages / 500
requests per month.

<img width="60%" alt="Showcase Universal Action" src="https://github.com/chrisgrieser/pdf-summarizer-alfred/assets/73286100/a4c8e7e7-cb56-4727-9a0e-ddfc91461c11">

<img alt="showcase" width=70% src="https://github.com/user-attachments/assets/5fd86ec0-469b-4a13-873f-6118169b7f06">

## Installation & Setup
[➡️ Download the latest release.](./releases/latest)

The workflow auto-updates via Alfred's workflow-update mechanism.

**Get a ChatPDF API key:**
1. Go to <https://www.chatpdf.com/>
2. Scroll to the bottom of the page.
3. In the footer, click `My Account`. You are prompted to create an account if
   you do not have one yet.
4. In `My Account`, expand the `Developer` settings. You can find your API key there:

<img src="./how-to-get-api-key.png" alt="how to find the API key" width=40%>

> [!NOTE]
> **Advanced Users:** Instead of entering the API key directly, you can also
> enter `.zshenv` into the API key field. The workflow then uses the key
> exported as `CHATPDF_API_KEY` in your `.zshenv`.

## Usage
Use the [Universal
Action](https://www.alfredapp.com/help/workflows/triggers/universal-actions/) or
the [hotkey](https://www.alfredapp.com/help/workflows/triggers/hotkey/) while
having selected a PDF file in Finder.

## Recommended Citation
Please cite this software project as (APA):

```txt
Grieser, C. (2023). PDF summarizer for Alfred [Computer software]. 
https://github.com/chrisgrieser/pdf-summarizer-alfred
```

For other citation styles, use the following metadata: [Citation File
Format](./CITATION.cff)

## Credits
In my day job, I am a sociologist studying the social mechanisms underlying the
digital economy. For my PhD project, I investigate the governance of the app
economy and how software ecosystems manage the tension between innovation and
compatibility. If you are interested in this subject, feel free to get in touch.

- [Academic Website](https://chris-grieser.de/)
- [Mastodon](https://pkm.social/@pseudometa)
- [ResearchGate](https://www.researchgate.net/profile/Christopher-Grieser)
- [LinkedIn](https://www.linkedin.com/in/christopher-grieser-ba693b17a/)

<a href='https://ko-fi.com/Y8Y86SQ91' target='_blank'> <img height='36'
style='border:0px;height:36px;' src='https://cdn.ko-fi.com/cdn/kofi1.png?v=3'
border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
