---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Translation"
product_tag: "translation"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java Word & Excel Document Translation SDK & REST API"
head_description: "Java document translation Cloud SDK & REST API. Translate English text to & from French, German, Chinese, Italian, Spanish, Russian, Arabic, Polish and Portuguese languages."

############################# Header ############################
title: "Document Translation REST API & Java SDK"
description: "Add features of documents and plain text translation in your Java applications using Cloud REST API. Accurately translate content between 10 most widely used business languages."
button:
    enable: true

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Translation Cloud SDK for Java"
        image: "/sdk/272x272/groupdocs_translation-for-java.webp"
        product: "GroupDocs.Translation"
        platform: "Java"

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
      GroupDocs.Translation Cloud SDK for Java makes it simple for developers translating the contents on Microsoft Word, Excel, PowerPoint and plain text documents without using any external software. The API employs a smart neural machine translation approach to translate text from Microsoft Word documents (paragraphs, tables, image captions, headers, footers, footnotes, endnotes), Excel Worksheets (charts, tables, cells, pivot tables) and PowerPoint presentations (text frames, header, footer, shapes, charts, smartart) into 22 language pairs. The SDK supports converting English text from supported document formats to and from French, German, Chinese, Italian, Spanish, Russian, Arabic, Polish and Portuguese languages while keeping the original document structure undisturbed.

      GroupDocs.Translation REST API can easily integrate into existing systems thus managing the low-level details of API requests and handling responses to boost up the overall productivity. You just need to pass out request parameters (path of source file name, format & folder, choose the language pair to translate between, mention the name of translated file, folder and location of the target file to be stored) and get the documents translated by adding a few lines of code.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          An overview of the main features supported by GroupDocs.Translation Cloud for Java.
      
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
          GroupDocs.Translation Cloud SDK for Java supports a number of document formats.

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
      - title: "Get Started with Document Translation REST API"
        content: "GroupDocs.Translation Cloud API comes with detailed developer guides and live code examples for all major programming languages to start working with API features in no time. Simply create a free account at GroupDocs Cloud, get APP SID & Key information to communicate with GroupDocs Cloud API and you are ready to make an API request on any platform using cURL commands or the SDKs of your choice."

      # more_feature_loop
      - title: "Translate Word document - Java"
        content: |
          
          
          ```java
            //Get your App SID, App Key and Storage Name at https://dashboard.groupdocs.cloud (free registration is required).

            import com.GroupDocs.translate.api.*;
            import com.GroupDocs.translate.Configuration;


            private static void setUpConfig() throws Exception {
                Configuration.setAPP_SID("XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX");
                Configuration.setAPI_KEY("XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX");
                }

            public String TranslateDocument() {
                String name = "test.docx";
                String folder = "";
                String pair = "en-fr";
                String format = "docx";
                String storage = "First Storage";
                String saveFile = "translation.docx";
                String savePath = "";
                boolean masters = false;
                ArrayList elements = new ArrayList();
                FileInfo fileInfo = new FileInfo(name, folder, pair, format, storage, saveFile, savePath, masters, elements);
                TranslationDocumentRequest translationDocumentRequest = new TranslationDocumentRequest(fileInfo.toString());
                TranslateDocumentResponse translateDocumentResponse = TranslationApi.TranslateDocument(translationDocumentRequest)
                return translateDocumentResponse.message;
            }
          ```
      # more_feature_loop
      - title: "Any Language, Platform and Storage Service Provider"
        content: "GroupDocs.Translation for Cloud is a REST based API that can easily be integrated with any language or platform, capable to manage HTTP requests and responses. It supports all popular cloud storage services such as Google Cloud, Drive, DropBox and Amazon S3 to interact without any dependencies."

      # more_feature_loop
      - title: "Translate plain text - Java"
        content: |
          
          
          ```shell
            //Get your App SID, App Key and Storage Name at https://dashboard.groupdocs.cloud (free registration is required).

            import com.GroupDocs.translate.api.*;
            import com.GroupDocs.translate.Configuration;


            private static void setUpConfig() throws Exception {
                Configuration.setAPP_SID("XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX");
                Configuration.setAPI_KEY("XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX");
                }

            static String TranslateText() {
                pair = "en-fr";
                text = "Text to translate";
                TextInfo textInfo = new TextInfo(pair, text);
                TranslationTextRequest translationTextRequest = new TranslationTextRequest(TextInfo.toString());
                TranslationTextResponse translateTextResponse = TranslationApi.TranslateText(translationTextRequest);
                return translateTextResponse.translation;
            }
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