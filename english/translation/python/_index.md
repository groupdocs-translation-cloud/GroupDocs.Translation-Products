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
head_title: "Python Word & Excel Document Translation SDK & REST API"
head_description: "Python document translation Cloud SDK & REST API. Translate English text to & from French, German, Chinese, Italian, Spanish, Russian, Arabic, Polish and Portuguese languages."

############################# Header ############################
title: "Python Document Translation REST API & SDK"
description: "Empower your applications and tools with document translation features using Python REST API and Cloud SDK."
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
      GroupDocs.Translation Cloud SDK for Python enables developers to get started with translation of Microsoft Word, Excel, PowerPoint and plain text documents within Python-based cloud applications. It supports converting English language text from supported file formats back and forth to other most popular business languages namely French, German, Chinese, Italian, Spanish, Russian, Arabic, Polish and Portuguese without disturbing the original document structure (paragraphs, tables, image captions, charts, smartart, header, footer, cells, pivot tables).

      GroupDocs.Translation Cloud SDK for Python has been built as a layer on top of GroupDocs.Translation Cloud REST API that saves valuable development time by managing low-level requests and handling responses. The developers can focus on writing up the specific code only as needed in the project.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          An overview of the main features supported by GroupDocs.Translation Cloud for Python.
      
        left:
          enable: true
          icon: "fas fa-crop"
          title: "Documents Translation"
          content: |
            * Translate Plain Text
            * Translate Word Documents
            * Translate Excel Worksheets
            * Translate PowerPoint Slides
        right:
          enable: true
          icon: "fas fa-file-alt"
          title: "Supported Languages"
          content: |
            * French to German & vice versa
            * French to Italian & vice versa
            * English to French & vice versa
            * English to Deutsch & vice versa
            * English to Chinese & vice versa
            * English to Spainish & vice versa
            * English to Italian & vice versa
            * English to Russian & vice versa
            * English to Arabic & vice versa
            * English to Polish & vice versa
            * English to Portuguese & vice versa
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Translation Cloud SDK for Python supports a number of document formats.

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office Formats"
              content: |
                * **Word**: DOC, DOCX, DOCM
                * **Excel**:  XLS, XLSX, XLSM
                * **PowerPoint**: PPT, PPTX, PPTM
                

        


      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Translation Cloud SDK for Python requires Python 2.7 or 3.4 or later.
      
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
    title: "Advanced Document Translation REST API Features"

    feature:
      # feature loop
      - icon: "fas fa-language"
        content: "Supports 10 languages and 22 language pairs"

      # feature loop
      - icon: "fas fa-copy"
        content: "Translation of tables in Word & PowerPoint documents"

      # feature loop
      - icon: "fas fa-file-alt"
        content: "Translation of headers and footers in Word & PowerPoint documents"
      
      # feature loop
      - icon: "fas fa-copy"
        content: "Translation of footnotes and endnotes in Word document"

      # feature loop
      - icon: "fas fa-file-image"
        content: "Translation of image captions in Word documents"

      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Translation of Text Frames, Charts & Slides within PowerPoint Presentations"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Translation of cells containing text in Excel workbooks"

      # feature loop
      - icon: "fas fa-chart-bar"
        content: "Translation of charts in Excel workbooks"

      # feature loop
      - icon: "fas fa-table"
        content: "Translation of tables in Excel workbooks"
      # feature loop
      - icon: "fas fa-random"
        content: "Translation of pivot tables in Excel workbooks"
      # feature loop
      - icon: "fas fa-lock"
        content: "APIs are secured and require authentication"
      # feature loop
      - icon: "fas fa-list"
        content: "API explorer based on swagger collection"
    
    more_feature:
      # more_feature_loop
      - title: "Working with Document Translation REST API"
        content: "GroupDocs.Translation Cloud API comes with detailed developer guides and live code examples for all major programming languages to start working with API features in no time. Simply create a free account at GroupDocs Cloud, get APP SID & Key information to communicate with GroupDocs Cloud API and you are ready to make an API request on any platform using cURL commands or the SDKs of your choice."

      # more_feature_loop
      - title: "Translate Word document - Python"
        content: |
          
          
          ```cs
            //Get your App SID, App Key and Storage Name at https://dashboard.groupdocs.cloud (free registration is required).

            from groupdocstranslationcloud.configuration import Configuration
            from groupdocstranslationcloud.api.translation_api import TranslationApi
            from groupdocstranslationcloud.models.translate_text import TranslateText
            from groupdocstranslationcloud.models.translate_document import TranslateDocument

            #enter valid apiKey and appSid
            configuration = Configuration(apiKey="", appSid="")
            api = TranslationApi(configuration)

            #document translation
            pair = "en-fr"
            _format = "docx"
            storage = "First Storage"
            name = "test.docx"
            folder = ""
            savepath = ""
            savefile = "test_python.docx"  
            masters = False
            elements = []
            translator = TranslateDocument(pair, _format, storage, name, folder, savepath, savefile, masters, elements)
            request = translator.to_string() 
            res_doc = api.post_translate_document(request)
            print(res_doc.message)
          ```
      # more_feature_loop
      - title: "Any Language, Platform and Storage Service Provider"
        content: "GroupDocs.Translation for Cloud is a REST based API that can easily be integrated with any language or platform, capable to manage HTTP requests and responses. It supports all popular cloud storage services such as Google Cloud, Drive, DropBox and Amazon S3 to interact without any dependencies."

      # more_feature_loop
      - title: "Translate plain text - Python"
        content: |
          
          
          ```cs
            //Get your App SID, App Key and Storage Name at https://dashboard.groupdocs.cloud (free registration is required).

            from groupdocstranslationcloud.configuration import Configuration
            from groupdocstranslationcloud.api.translation_api import TranslationApi
            from groupdocstranslationcloud.models.translate_text import TranslateText
            from groupdocstranslationcloud.models.translate_document import TranslateDocument

            #enter valid apiKey and appSid
            configuration = Configuration(apiKey="", appSid="")
            api = TranslationApi(configuration)

            pair = "en-fr"
            text = "Welcome to Paris"
            translator = TranslateText(pair, text)
            request = translator.to_string()
            res_text = api.post_translate_text(request)
            print(res_text.translation)
          ```
      # more_feature_loop
      - title: "Security and Authentication"
        content: "The GroupDocs.Translation Cloud API is SSL secured and the authentication requests require a signature and AppSID query parameters or OAuth 2.0 authorization header."
      

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Translation Cloud also offers document translation SDKs for other languages as listed below:"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer Cloud SDK for cURL"
          image: "/sdk/272x272/groupdocs_translation-for-curl.webp"
          product: "GroupDocs.Viewer"
          platform: "cURL"
          link: "/translation/curl/"

        # solution loop
        - img_alt: "GroupDocs.Viewer Cloud SDK for .NET"
          image: "/sdk/272x272/groupdocs_translation-for-net.webp"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/translation/net/"

        # solution loop
        - img_alt: "GroupDocs.Viewer Cloud SDK for Java"
          image: "/sdk/272x272/groupdocs_translation-for-java.webp"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/translation/java/"

        

        # solution loop
        - img_alt: "GroupDocs.Viewer Cloud SDK for Python"
          image: "/sdk/272x272/groupdocs_translation-for-python.webp"
          product: "GroupDocs.Viewer"
          platform: "Python"
          link: "/translation/python/"

      

     

        

############################# Back to top ###############################
back_to_top:
  enable: true
---