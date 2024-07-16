<h1 align="center" id="title">Mailiza?</h1><br>

<p align="center"><img src="Mailiza-Logo.png"></p><br>

<p id="description">Mailiza, based on WhatMail is a command-line tool that analyzes the header of an email and provides detailed information about various fields. It extracts commonly recognized email header fields such as To From Subject Date Delivered-To as well as useful fields like Message-ID Return-Path Reply-To X-Headers MIME Version Content Type Received-SPF DKIM Signature Authentication-Results X-Mailer and DMARC Results. <br><br>This tool is useful for forensic analysis investigating email authenticity understanding email routing and gathering information about the email sender and recipient. The output is presented in a tabular format making it easy to read and analyze.</p><br>

<p align="center"><img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="shields"><img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="shields"><img src="https://img.shields.io/badge/Vscode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"&amp;style=for-the-badge&amp;logo=PyCharm&amp;logoColor=white" alt="shields"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="shields"></p><br>



  
  <h2>💻 Filters Supported:</h2><br>

*   Message-ID
*   Return-Path
*   Reply-To
*   X-Headers
*   MIME Version
*   Content Type
*   Received-SPF
*   DKIM Signature
*   Authentication Results
*   X-Mailer
*   DMARC Results

<br><h2>🛠️ Installation Steps:</h2>

```
git clone https://github.com/1hecha0s/Mailiza
```

```
cd Mailiza
```

```
pip install colorama tabulate
```

```
python Mailiza.py -hf {Path_to_header_file}
```
<br><h2>🎓 Usage:</h2>
``` 
python Mailiza.py -hf header.txt
```
<br>
Analyzes the email header in the 'header.txt' file and displays the results on the console.

<br>
<br>

```
python Mailiza.py -hf header.txt -O analysis_results.txt
```
<br>
        Analyzes the email header in the 'header.txt' file and saves the analysis results in the 'analysis_results.txt' file.


