---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Translation"
product_tag: "translation"
platform: "cURL"
platform_tag: "curl"

############################# Head ############################
head_title: "Translate texts and documents from the command line"
head_description: "Interact with translation REST API directly from the command line or Bash scripts without installing any software. Translate texts and documents to and from English, French, Chinese, Spanish, German, Italian, Russian, Arabic, Polish and other languages."

############################# Header ############################
title: "Translate texts and documents from the command line"
description: "Interact with translation REST API directly from the command line or Bash scripts without installing any software. Translate texts and documents to and from English, French, Chinese, Spanish, German, Italian, Russian, Arabic, Polish and other languages."
button:
    enable: true

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Translation Cloud"
        image: "/sdk/272x272/groupdocs_translation-for-curl.webp"
        product: "GroupDocs.Translation"
        platform: "cURL"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Overview"

            # button loop
            - link: "#features"
              text: "Features"


            # button loop
            - link: "https://docs.groupdocs.cloud/translation/release-notes/"
              text: "Release Notes"

            # button loop
            - link: "https://purchase.groupdocs.cloud/pricing"
              text: "Pricing"

    right:
        link_download: "https://github.com/groupdocs-translation-cloud/"
        link_learn: "https://docs.groupdocs.cloud/translation/"
        link_buy: "https://purchase.groupdocs.cloud/buy"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Translation offers real-time machine translation for texts, documents, images and resources. Powerful machine learning algorithms and sophisticated neural networks provide a quality close to that of a professional human translator, but much faster and more cost-effective. Running on a high-performance cloud server hosted by GroupDocs, it can translate PDF, Microsoft Office and OpenOffice documents, Markdown files, images and .NET resources into 46 European, Middle East and Asian languages (across 128 language pairs). The API not only translates text, but also accurately preserves metadata, structure, styles, and layout of documents.

      The service provides a versatile and easy-to-use REST API, which can be accessed without installing any software. Just use cURL commands and combine them into scripts for complex tasks. You can also use third party REST API tools like Postman. This allows you to use GroupDocs.Translation on any platform with an internet connection, even those not yet covered by the SDK.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Main capabilities of GroupDocs.Translation Cloud
      
        left:
          enable: true
          icon: "fas fa-crop"
          title: "Supported content"
          content: |
            * Plain text
            * Microsoft Word
            * Microsoft Excel
            * Microsoft PowerPoint
            * OpenOffice
            * PDF
            * HTML
            * Markdown
            * Hugo content
            * Images
            * .NET resources
            * Subtitles (.srt format)
        right:
          enable: true
          icon: "fas fa-file-alt"
          title: "Supported languages"
          content: |
            * Afrikaans
            * Arabic
            * Armenian
            * Azerbaijani
            * Bengali
            * Bulgarian
            * Catala
            * Chinese
            * Croatian
            * Czech
            * Danish
            * Dutch
            * English
            * Estonian
            * Farsi
            * Finnish
            * French
            * Georgian
            * German
            * Greek
            * Hebrew
            * Hindi
            * Hungarian
            * Indonesian
            * Irish
            * Italian
            * Japanese
            * Korean
            * Latvian
            * Lithuanian
            * Malay
            * Norwegian
            * Polish
            * Portuguese
            * Romanian
            * Russian
            * Serbian
            * Slovak
            * Spanish
            * Swedish
            * Tagalog
            * Thai
            * Turkish
            * Ukrainian
            * Urdu
            * Vietnamese
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Translation Cloud supports all popular document formats

        left:
          enable: true
          table:
            # table loop
            - title: "Office documents"
              content: |
                * **Microsoft Word**: DOC, DOCX, DOCM
                * **Microsoft Excel**:  XLS, XLSX, XLSM
                * **Microsoft PowerPoint**: PPT, PPTX, PPTM
                * **OpenOffice**: ODT, ODS, ODP
                
        right:
          enable: true
          table:
            # table loop
            - title: "Other formats"
              content: |
                * **PDF**
                * **Markdown**
                * **CSV** & **TSV**
                * **RTF**
                * **TXT**
        


      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Translation Cloud for cURL works on any device or platform with Internet connection
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Operating Systems"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Supported Frameworks"
              content: |
                * Java 7 (1.7) and above

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "Development Environments"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "Build Automation Tool"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "Advanced features of document translation REST API"

    feature:
      # feature loop
      - icon: "fas fa-language"
        content: "Translates to and from 46 European, Middle East and Asian languages"

      # feature loop
      - icon: "fas fa-table"
        content: "Translates tables in Word documents and PowerPoint presentations"

      # feature loop
      - icon: "fas fa-file-alt"
        content: "Translates headers and footers in documents"
      
      # feature loop
      - icon: "fas fa-copy"
        content: "Translates footnotes and endnotes in Word documents"

      # feature loop
      - icon: "fas fa-file-image"
        content: "Translates image captions in Word documents"

      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Translates text frames, charts and slides in PowerPoint presentations"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Translates texts inside spreadsheet cells"

      # feature loop
      - icon: "fas fa-chart-bar"
        content: "Translates charts and pivot tables in Excel workbooks"

      # feature loop
      - icon: "fas fa-code"
        content: "Translates Markdown files preserving all common Markdown formatting"

      # feature loop
      - icon: "fas fa-link"
        content: "Translates files from URLs and public repositories"

      # feature loop
      - icon: "fas fa-random"
        content: "Converts results into different formats without additional software"

      # feature loop
      - icon: "fas fa-list"
        content: "API explorer based on Swagger collection"
    
    more_feature:
      # more_feature_loop
      - title: "Any language, platform and storage service provider"
        content: "GroupDocs.Translation is a REST API that can easily be integrated into any application written in any programming language capable of handling HTTP requests and responses. It natively supports all popular cloud storage services such as Google Cloud, Drive, DropBox and Amazon S3 to interact without any dependencies."

      # more_feature_loop
      - title: "Quick start with Translation REST API"
        content: "GroupDocs.Translation Cloud API comes with detailed developer references and live code examples for all major programming languages to start working with API features in no time. Simply create a free account at GroupDocs Cloud, get APP SID & Key information to communicate with GroupDocs Cloud API and you are ready to make an API request on any platform using cURL commands."

      # more_feature_loop
      - title: "Translate text - cURL"
        content: |
          
          
          ```shell
            //Get your App SID, App Key and Storage Name at https://dashboard.groupdocs.cloud (free registration is required).
            // Getting token
            curl --location --reqest POST 'https://id.groupdocs.cloud/connect/token' \
                --header 'Content-Type: application/x-www-form-urlencoded' \
                --data-urlencode 'grant_type=client_credentials' \
                --data-urlencode 'client_id=CLIENT-ID-VALUE' \
                --data-urlencode 'client_secret=CLIENT-SECRET-VALUE'

            //response

            {
                "access_token": "eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9...BUNNec2iRtStPW2Ywek4iJmYwMbWONQ",
                "expires_in": 3600,
                "token_type": "Bearer"
            }

            // Sending text for translation
            curl --location --request POST 'https://api.groupdocs.cloud/v2.0/translation/text' \
                --header 'Content-Type: application/json' \
                --header 'Authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9...UV1hLfgNCSQ4VKGCOA' \
                --data '{
                    "sourceLanguage": "en",
                    "targetLanguages": [
                        "de"
                    ],
                    "texts": [
                        "Hello, world! I can read this text in my language."
                    ]
                }'
	
            //response
	
            {
                "status": 202,
                "message": "Starting translation",
                "id": "a4fc6c6e-81b0-43c8-b62b-b8bb99520ce9"
            }
	
            //getting translation
            curl --request GET --location 'https://api.groupdocs.cloud/v2.0/translation/text/a4fc6c6e-81b0-43c8-b62b-b8bb99520ce9' \
                --header 'Authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9...UV1hLfgNCSQ4VKGCOA'	
	
            //response
	
            {
                "status": 200,
                "message": "Text translated successfully",
                "translations": {
                    "de": [
                        "Hallo, Welt! Ich kann diesen Text in meiner Sprache lesen."
                    ]
                }
            }	
          ```
      

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Translation Cloud offers SDKs for popular programming languages and platforms:"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Translation Cloud SDK for .NET"
          image: "/sdk/272x272/groupdocs_translation-for-net.webp"
          product: "GroupDocs.Translation"
          platform: ".NET"
          link: "/translation/net/"

        # solution loop
        - img_alt: "GroupDocs.Translation Cloud SDK for Java"
          image: "/sdk/272x272/groupdocs_translation-for-java.webp"
          product: "GroupDocs.Translation"
          platform: "Java"
          link: "/translation/java/"

        # solution loop
        - img_alt: "GroupDocs.Translation Cloud SDK for Python"
          image: "/sdk/272x272/groupdocs_translation-for-python.webp"
          product: "GroupDocs.Translation"
          platform: "Python"
          link: "/translation/python/"        

        # solution loop
        - img_alt: "GroupDocs.Translation Cloud SDK for Android"
          image: "/sdk/272x272/groupdocs_translation-for-android.webp"
          product: "GroupDocs.Translation"
          platform: "Android"
          link: "/translation/android/"
          

############################# Back to top ###############################
back_to_top:
  enable: true
---