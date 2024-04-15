---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Translation"
product_tag: "translation"
platform: "Python"
platform_tag: "python"

############################# Head ############################
head_title: "Translate texts and documents in your Python applications"
head_description: "Create cross-platform data science, AI, and automation solutions in Python based on GroupDocs.Translation API. Focus on business logic rather than the technical details."

############################# Header ############################
title: "Python Cloud SDK for text and document translation"
description: "Create cross-platform data science, AI, and automation solutions in Python based on GroupDocs.Translation API. Focus on business logic rather than the technical details."
button:
    enable: true

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Translation Cloud SDK for Python"
        image: "/sdk/272x272/groupdocs_translation-for-python.webp"
        product: "GroupDocs.Translation"
        platform: "Python"

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
        link_download: "https://groupdocscloud.github.io/"
        link_learn: "https://docs.groupdocs.cloud/translation/"
        link_buy: "https://purchase.groupdocs.cloud/buy"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Translation offers real-time machine translation for texts, documents, images and resources. Powerful machine learning algorithms and sophisticated neural networks provide a quality close to that of a professional human translator, but much faster and more cost-effective. Running on a high-performance cloud server hosted by GroupDocs, it can translate PDF, Microsoft Office and OpenOffice documents, Markdown files, and .NET resources into 46 European, Middle East and Asian languages (across 128 language pairs). The API not only translates text, but also accurately preserves metadata, structure, styles, and layout of documents.

      This SDK greatly simplifies the interaction with GroupDocs.Translation Cloud services from Python code, allowing you to focus on business logic rather than the technical details. It handles all the routine operations such as establishing connections, sending API requests, and parsing responses, wrapping all these tasks into a few simple methods that can be used in any Python application or workbook. The Python SDK, demo applications, documentation, and examples are open source distributed under the MIT license. You can use them for any purpose and change any part of the code.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Main capabilities of GroupDocs.Translation Cloud SDK for Python
      
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
          GroupDocs.Translation Cloud SDK for Python supports all popular document formats

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
          GroupDocs.Translation Cloud SDK for Python works with Python 2.7 or 3.4 or later.
      
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
    title: "Advanced features of GroupDocs.Translation Cloud SDK for Python"

    feature:
      # feature loop
      - icon: "fas fa-language"
        content: "Supports 46 languages and 128 language pairs"

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
        content: "Detailed developer reference based on Swagger collection"
    
    more_feature:
      # more_feature_loop
      - title: "Quick start with document translation SDK for Python"
        content: "GroupDocs.Translation Cloud SDK for Python comes with detailed developer guides and live code examples to start working with API features in no time. Simply create a free account at GroupDocs Cloud, get APP SID & Key information to communicate with GroupDocs Cloud API and you are ready to make an API and you are ready to use the SDK."

      # more_feature_loop
      - title: "Any language, platform and storage service provider"
        content: "GroupDocs.Translation Cloud is a REST API that can easily be integrated with any language or platform, capable to manage HTTP requests and responses. It supports all popular cloud storage services such as Google Cloud, Drive, DropBox and Amazon S3 to interact without any dependencies."

      # more_feature_loop
      - title: "Translate plain text in Python"
        content: |
          
          
          ```python
            //Get your App SID, App Key and Storage Name at https://dashboard.groupdocs.cloud (free registration is required).

            import time
            import groupdocs_translation_cloud
            from groupdocs_translation_cloud import TextRequest, PdfFileRequest, Format
            api = groupdocs_translation_cloud.api.TranslationApi()
            file_api = groupdocs_translation_cloud.api.FileApi()
            api.api_client.configuration.client_id = "YOU_CLIENT_ID"
            api.api_client.configuration.client_secret = "YOU_CLIENT_SECRET"
            text_request = TextRequest(source_language="en", 
            						   target_languages=["es", "fr", "ru"], 
            						   texts=["Hello World!", "This is a test text"], 
            						   origin="your_application_name", 
            						   contains_markdown=False)
            response = api.text_post(text_request)
            if response.status == 202:
                while True:
                    status_response = api.text_request_id_get(response.id)
                    if status_response.status == 200:
                    	for lang in status_response.translations:
                    		print(lang + ": " + status_response.translations[lang][0])
                    		break
                    time.sleep(2)
          ```
      # more_feature_loop
      - title: "Security and authentication"
        content: "The GroupDocs.Translation Cloud API is SSL secured and the authentication requests require a signature and AppSID query parameters or OAuth 2.0 authorization header."
      

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Translation Cloud offers SDKs for popular programming languages and platforms:"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Translation Cloud SDK for cURL"
          image: "/sdk/272x272/groupdocs_translation-for-curl.webp"
          product: "GroupDocs.Translation"
          platform: "cURL"
          link: "/translation/curl/"

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
        - img_alt: "GroupDocs.Translation Cloud SDK for Android"
          image: "/sdk/272x272/groupdocs_translation-for-android.webp"
          product: "GroupDocs.Translation"
          platform: "Android"
          link: "/translation/android/"      

     

        

############################# Back to top ###############################
back_to_top:
  enable: true
---