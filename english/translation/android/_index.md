---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Translation"
product_tag: "translation"
platform: "Android"
platform_tag: "android"

############################# Head ############################
head_title: "Translate texts and documents in your Android apps"
head_description: "Add translation features to apps for Android devices using GroupDocs.Translation API. Bring translation to any system – from entry-level netbooks to smartphones."

############################# Header ############################
title: "Android Cloud SDK for text and document translation"
description: "Add translation features to apps for Android devices using GroupDocs.Translation API. Bring translation to any system – from entry-level netbooks to smartphones."
button:
    enable: true

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Translation Cloud SDK for Android"
        image: "/sdk/272x272/groupdocs_translation-for-android.webp"
        product: "GroupDocs.Translation"
        platform: "Android"

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

      This SDK greatly simplifies the interaction with GroupDocs.Translation Cloud services from Android apps, allowing you to focus on business logic rather than the technical details. It handles all the routine operations such as establishing connections, sending API requests, and parsing responses, wrapping all these tasks into a few simple methods. The translation is carried out by high-performance cloud servers. You can use the application on any system – from entry-level netbooks to smartphones.

      The Android SDK, demo applications, documentation, and examples are open source distributed under the MIT license. You can use them for any purpose and change any part of the code.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Main capabilities of GroupDocs.Translation Cloud SDK for Android
      
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
          GroupDocs.Translation Cloud SDK for Android supports all popular document formats

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
         GroupDocs.Translation Cloud SDK for Android works on any Android device - from smartphones to Chromebooks
      
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
    title: "Advanced features of GroupDocs.Translation Cloud SDK for Android"

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
      - title: "Get started with document translation SDK for Android"
        content: "GroupDocs.Translation Cloud SDK for Android comes with detailed developer guides and live code examples to start working with API features in no time. Simply create a free account at GroupDocs Cloud, get APP SID & Key information to communicate with GroupDocs Cloud API."

      # more_feature_loop
      - title: "Any language, platform and storage service provider"
        content: "GroupDocs.Translation for Cloud is a REST API that can easily be integrated with any language or platform, capable to manage HTTP requests and responses. It supports all popular cloud storage services such as Google Cloud, Drive, DropBox and Amazon S3 to interact without any dependencies."

      # more_feature_loop
      - title: "Translate plain text in Android"
        content:           
          ```java
package com.groupdocs;
// Import classes

import com.groupdocs.model.*;
import org.openapitools.client.api.TranslationApi;

public class TextDemo {
    public static void main(String[] args) {
        String basePath = "https://api.groupdocs.cloud/v2.0/translation";
        String cliendId = "YOUR_CLIENT_ID";
        String clientSecret = "YOUR_CLIENT_SECRET";

        ApiClient defaultClient = new ApiClient(basePath, cliendId, clientSecret, null);
        TranslationApi translationApi = new TranslationApi(defaultClient);

        TextRequest request = new TextRequest();

        request.setSourceLanguage("en");
        request.addTargetLanguagesItem("de");
        request.addTextsItem("Text to translate");
        request.setOrigin("");
        
        try {
            String r = translationApi.textPost(request).getId();
            CloudTextResponse response = translationApi.textRequestIdGet(r);
            if (!response.getStatus().toString().equals("500")) {
                while (true) {
                    response = translationApi.textRequestIdGet(r);
                    if (response.getStatus().toString().equals("200")) {
                        System.out.println(response);
                        break;

                    }
                    try {
                        Thread.sleep(2000);
                    } catch (InterruptedException e) {
                        e.printStackTrace();
                    }

                }
            }
        }
        catch(ApiException e){
            System.err.println("Exception when calling TranslationApi#textPost");
            System.err.println("Status code: " + e.getCode());
            System.err.println("Reason: " + e.getResponseBody());
            System.err.println("Response headers: " + e.getResponseHeaders());
            e.printStackTrace();
        }
    }
}
            
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
        - img_alt: "GroupDocs.Translation Cloud SDK for Python"
          image: "/sdk/272x272/groupdocs_translation-for-python.webp"
          product: "GroupDocs.Translation"
          platform: "Python"
          link: "/translation/python/"

     

        

############################# Back to top ###############################
back_to_top:
  enable: true
---