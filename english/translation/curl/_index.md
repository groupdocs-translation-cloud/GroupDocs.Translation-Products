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
head_title: "Translate English Text from Word & Excel Documents via cURL Commands"
head_description: "Translate text from Word and Excel worksheets via cURL commands. Supports translating English to & from French, German, Chinese, Italian, Spanish, Russian or other languages"

############################# Header ############################
title: "Translate Documents using cURL"
description: "Communicate with document translation REST API to precisely translate plain text and contents of Word, Excel, PowerPoint, PDF, OpenDocument & Markdown documents in popular business languages without installing any external software."
button:
    enable: true

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Translation for Cloud"
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
      GroupDocs.Translation Cloud for cURL is a flexible text and documents translation solution to transform text-based content on your cloud-hosted Microsoft Word, Excel, PowerPoint, PDF, OpenDocument & Markdown documents across 68 language pairs. Simply use cURL commands to send requests to the REST API, translate English language content from the supported document types to French, German, Chinese, Italian, Spanish, Russian, Arabic, Polish or other languages, and back again.

      The API precisely reads the text within the contents of Word documents and ODT files (tables, headers, footers, image captions, footnotes, endnotes), PowerPoint presentations and ODP files (text frames, header, footer, shapes, charts, smartart), Excel spreadsheets and ODS files (charts, tables, pivot tables) and PDF files without affecting the layout and properties of the original source document.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          An overview of the main features supported by GroupDocs.Translation Cloud.
      
        left:
          enable: true
          icon: "fas fa-crop"
          title: "Documents Translation"
          content: |
            * Translate Plain Text
            * Translate Word Documents
            * Translate Excel Worksheets
            * Translate PowerPoint Slides
            * Translate PDF Documents
            * Translate Markdown files
            * Translate OpenDocument files
        right:
          enable: true
          icon: "fas fa-file-alt"
          title: "Supported Languages"
          content: |
            * French to German & vice versa
            * French to Italian & vice versa
            * French to Arabic & vice versa
            * English to French & vice versa
            * English to Deutsch & vice versa
            * English to Chinese & vice versa
            * English to Spainish & vice versa
            * English to Italian & vice versa
            * English to Russian & vice versa
            * English to Arabic & vice versa
            * English to Polish & vice versa
            * English to Portuguese & vice versa
            * English to Ukrainian & vice versa
            * English to Vietnamese & vice versa
            * English to Indonesian & vice versa
            * English to Hindi & vice versa
            * English to Greek & vice versa
            * English to Dutch & vice versa
            * English to Swedish & vice versa
            * English to Hungarian & vice versa
            * English to Turkish & vice versa
            * English to Japanese & vice versa
            * English to Korean & vice versa
            * English to Czech & vice versa
            * English to Finnish & vice versa
            * English to Irish & vice versa
            * English to Slovak & vice versa
            * English to Farsi & vice versa
            * English to Hebrew & vice versa
            * English to Azerbaijani & vice versa 
            * English to Thai & vice versa
            * English to Romanian & vice versa
            * English to Malay & vice versa 
            * English to Bulgarian & vice versa
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Annotation Cloud supports a number of document formats including almost all common business document and image file formats.

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office Formats"
              content: |
                * **Word**: DOC, DOCX, DOCM
                * **Excel**:  XLS, XLSX, XLSM
                * **PowerPoint**: PPT, PPTX, PPTM
                * **OpenDocument**: ODT, ODS, ODP
                
        right:
          enable: true
          table:
            # table loop
            - title: "Other Formats"
              content: |
                * **PDF**
                * **Markdown**
                * **CSV**
                * **TSV**
                * **RTF**
                * **TXT**
        


      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Translation Cloud for cURL - some of the supported languages and platforms.
      
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
        content: "Supports 32 languages and 68 language pairs"

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
      - title: "Any Language, Platform and Storage Service Provider"
        content: "GroupDocs.Translation for Cloud is a REST based API that can easily be integrated with any language or platform, capable to manage HTTP requests and responses. It supports all popular cloud storage services such as Google Cloud, Drive, DropBox and Amazon S3 to interact without any dependencies. "

      # more_feature_loop
      - title: "Translate Word document - cURL"
        content: |
          
          
          ```shell
          //Get your App SID, App Key and Storage Name at https://dashboard.groupdocs.cloud (free registration is required).
          curl -X POST "https://api.groupdocs.cloud/v1.0/translation/document" \
          -H "Authorization: Bearer TOKEN" \
          -H "Content-Type: application/json" \
          -d "'[{\"format\": \"docx\", \"pair\": \"en-fr\", \"name\": \"test.docx\", \"folder\": \"\", \"savepath\": \"\", \"savefile\": \"translated.docx\", \"storage\": \"First Storage\"}]'"

          and response

          {
              "status": "ok",
              "message": "word file saved successfully"
          }
          ```
      # more_feature_loop
      - title: "Quick Start with Document Translation REST API"
        content: "GroupDocs.Translation Cloud API comes with detailed developer guides and live code examples for all major programming languages to start working with API features in no time. Simply create a free account at GroupDocs Cloud, get APP SID & Key information to communicate with GroupDocs Cloud API and you are ready to make an API request on any platform using cURL commands or the SDKs of your choice."

      # more_feature_loop
      - title: "Translate plain text - cURL"
        content: |
          
          
          ```shell
            //Get your App SID, App Key and Storage Name at https://dashboard.groupdocs.cloud (free registration is required).
            curl -X POST "https://api.groupdocs.cloud/v1.0/translation/text" \
            -H "Authorization: Bearer TOKEN" \
            -H "Content-Type: application/json" \
            -d "'[{\"pair\": \"en-fr\", \"text\": \"Welcome to Paris\"}]'"

            //and response

            {
                "status": "ok",
                "message": "Text translated successfully",
                "translation": "Bienvenue à Paris"
            }
          ```
      

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Translation Cloud also offers individual document translation SDKs for other popular languages as listed below:"

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