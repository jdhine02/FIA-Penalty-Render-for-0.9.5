# FIA-Penalty-Render-for-0.9.5
An FIA style render for F1.  Can be interchangable for other series via logos.

## Install

Step 1: Download and extract the all files.

Step 2: Place the Penalties file from Compoenets into the existing theme's components file.  If a components file does not currently exist, just copy the components file into the the desired theme.

Step 3: Place event_penalties & driver_penalties folders into the desired theme's Layouts folder.

Step 4: Place the sperator.png and logotypes file into the desired theme's images folder.  If a image folder does not currently exist, just copy the images file in the desired theme.

Step 5: Add the following text section into the desired theme's global_var file:

    //hines added
    "FIAFontSize": "28",
    "FIAText": "#000000",
    "FIALine": "#000000",
    "FIAGrandPrix": "#ff1801",
    "FIAMarginDetailsArea": "50,0,50,0",
    "FIALeftBlockWidth" : "290",
    "FIARightBlockWidth" : "1500",
    "FIAFont": "Formula1-Regular",
    "FIAFontWide": "Formula1-Wide",
    "FIAFontBold" :"Formula1-Bold",
    "PenaltySeparator": "#000000",
    "FIABGColor" : "#09FFFFFF",

Step 6: Add the following text section into the desired theme's localization folder:

        //gp extended name
        "BAHRAIN GRAND PRIX": "GULF AIR BAHRAIN GRAND PRIX",
        "JEDDAH GRAND PRIX" : "STC SAUDI ARABIAN GRAND PRIX",
        "MELBOURNE GRAND PRIX": "ROLEX AUSTRALIAN GRAND PRIX",
        "SUZUKA GRAND PRIX" : "MSC CRUISES JAPANESE GRAND PRIX",
        "SHANGHAI GRAND PRIX" : "LENOVO CHINESE GRAND PRIX",
        "MIAMI GRAND PRIX": "CYRPTO.COM MIAMI GRAND PRIX",
        "IMOLA GRAND PRIX": "MSC CRUISES GRAN PREMIO DELL'EMILIA-ROMAGNA",
        "MONACO GRAND PRIX": "GRAND PRIX DE MONACO",
        "MONTREAL GRAND PRIX" : "AWS GRAND PRIX DU CANADA",
        "BARCELONA GRAND PRIX" : "ARAMCO GRAN PREMIO DE ESPAÑA",
        "SPIELBERG GRAND PRIX" : "QATAR AIRWAYS AUSTRIAN GRAND PRIX",
        "SILVERSTONE GRAND PRIX" : "QATAR AIRWAYS BRITISH GRAND PRIX",
        "HUNGARORING GRAND PRIX" : "HUNGARIAN GRAND PRIX",
        "SPA-FRANCORCHAMPS GRAND PRIX" : "ROLEX BELGIAN GRAND PRIX",
        "ZANDVOORT GRAND PRIX" : "HEINEKEN DUTCH GRAND PRIX",
        "MONZA GRAND PRIX" : "PIRELLI GRAN PREMIO D'ITALIA",
        "BAKU GRAND PRIX" : "QATAR AIRWAYS AZERBAIJAN GRAND PRIX",
        "MARINA BAY GRAND PRIX": "SINGAPORE AIRLINES SINGAPORE GRAND PRIX",
        "AUSTIN GRAND PRIX" : "PIRELLI UNITED STATES GRAND PRIX",
        "MEXICO GRAND PRIX": "GRAN PREMIO DE LA CIUDAD DE MÉXICO",
        "INTERLAGOS GRAND PRIX" : "LENOVO GRANDE PRÊMIO DE SÃO PAULO",
        "LOSAIL GRAND PRIX": "QATAR AIRWAYS QATAR GRAND PRIX",
        "LAS VEGAS GRAND PRIX": "HEINEKEN SILVER LAS VEGAS GRAND PRIX",
        "YAS MARINA GRAND PRIX" : "ETIHAD AIRWAYS ABU DHABI GRAND PRIX",
        "PAUL RICARD GRAND PRIX" : "GRAND PRIX DE FRANCE",
        "PORTIMÃO GRAND PRIX" : "GRANDE PRÉMIO DE PORTUGAL",

Credit goes to Dark373 for GP names.
![penalties](https://github.com/user-attachments/assets/1cfd539c-26b1-446b-9756-242e01a5fb02)
![penalty](https://github.com/user-attachments/assets/1c47bef3-00ef-4c4e-b460-0f594645bf21)


