# html Cerignola

Questo progetto ha l'obiettivo di spiegare come è stato creato il [sito](https://mzzntn.github.io) per il TPL di Cerignola.

Il sito è è creato grazie a [gtfs-to-html](https://github.com/blinktaginc/gtfs-to-html) andando a configurare in maniera opportuna i file  **confing.json** e **timetables.txt** contenuti al suo interno.

Alternativamente si puo configurare il **customize options** sul sito messo a disposizione dal progetto https://gtfstohtml.com/

    {
      "beautify": true,
      "coordinatePrecision": 5,
      "dateFormat": "DD-MM-YYYY",
      "daysShortStrings": ["Lun", "Mar", "Mer", "Gio", "Ven", "Sab", "Dom"],
      "daysStrings": ["lunedì", "martedì", "mercoledì", "giovedì", "venerdì", "sabato", "domenica"],
      "defaultOrientation": "horizontal",
      "EffectiveDate": "01-09-2019",
      "interpolatedStopSymbol": null,
      "linkStopUrls": false,
      "mapboxAccessToken": "pk.eyJ1IjoibXp6bnRuIiwiYSI6ImNqenpnMGM2ajE0a3MzbG8xMjV6ZjBuYzgifQ.80nc_zq59i5m2crvztv0Yw",
      "menuType": "simple",
      "noDropoffSymbol": "‡",
      "noDropoffText": "No drop off available",
      "noHead": false,
      "noPickupSymbol": "***",
      "noPickupText": "No pickup available",
      "noServiceSymbol": "Ø",
      "noServiceText": "Fermata non effettuata",
      "outputFormat": "html",
      "requestDropoffSymbol": "†",
      "requestDropoffText": "Must request drop off",
      "requestPickupSymbol": "***",
      "requestPickupText": "Request stop - call for pickup",
      "serviceNotProvidedOnText": "Service not provided on",
      "serviceProvidedOnText": "Service provided on",
      "showArrivalOnDifference": 0.2,
      "showMap": true,
      "showOnlyTimepoint": false,
      "showRouteTitle": true,
      "showStopCity": false,
      "showStopDescription": false,
      "sortingAlgorithm": "common",
      "timeFormat": "HH:mm"
    }
