# Test2.0
mit timestopper
{
  "title" : "logisches-schnelles-Denken",
  "pages" : [ {
    "actions" : [ "continue" ],
    "timelimit" : null,
    "items" : [ {
      "type" : "textmessage",
      "content" : "Hallo! Herzlich Willkommen auf meiner Testplattform. Zu allererst möchte ich mich bei euch ganz herzlich bedanken, dass ihr an meiner Arbeit teilnehmen wollt:"
    }, {
      "type" : "textmessage",
      "content" : "Nun bitte ich euch das Geschlecht anzugeben:"
    }, {
      "type" : "multiplechoice",
      "id" : "frage1",
      "answers" : [ {
        "value" : "1",
        "text" : "männlich"
      }, {
        "value" : "2",
        "text" : "weiblich"
      } ]
    }, {
      "type" : "textmessage",
      "content" : "Damit ihr die Aufgaben richtig versteht, gibt es einen Probelauf. Die Aufgaben basieren auf schnelles, logisches Denken. Bei den meisten Aufgaben werden keine Anleitung angegeben sein. Ihr müsst so schnell wie möglich eine sinngemässe Lösung finden. Ich prüfe wie schnell ihr Zusammenhänge erschliessen, Muster erkennen und von etwas Bekanntem auf etwas Unbekanntem schliessen könnt:"
    }, {
      "type" : "textmessage",
      "content" : "Probelauf: Eannab"
    }, {
      "type" : "multiplechoice",
      "id" : "frage2",
      "answers" : [ {
        "value" : "1",
        "text" : "Nabena"
      }, {
        "value" : "2",
        "text" : "Annabe"
      }, {
        "value" : "3",
        "text" : "Banane"
      } ]
    }, {
      "type" : "pagestopwatch",
      "id" : "stopwatch1"
    } ]
  }, {
    "actions" : [ "continue" ],
    "timelimit" : null,
    "items" : [ {
      "type" : "textmessage",
      "content" : "1 | 2| 3 | 5 | 8 | 13 | 21 | ?"
    }, {
      "type" : "textinput",
      "id" : "frage3"
    } ]
  }, {
    "actions" : [ "continue" ],
    "timelimit" : null,
    "items" : [ {
      "type" : "textmessage",
      "content" : "Wie sind Sie auf die Lösung von der vorherigen Aufgabe gekommen?"
    }, {
      "type" : "textinput",
      "id" : "frage4"
    } ]
  }, {
    "actions" : [ "continue" ],
    "timelimit" : null,
    "items" : [ {
      "type" : "textmessage",
      "content" : "Kontaktinformationen = Nenoitamrofnitkatnok"
    }, {
      "type" : "textmessage",
      "content" : "Reaktionsgeschwindigkeit = ?"
    }, {
      "type" : "textinput",
      "id" : "frage5"
    } ]
  }, {
    "actions" : [ "continue" ],
    "timelimit" : null,
    "items" : [ {
      "type" : "textmessage",
      "content" : "Was ist der Schlüssel für die vorherige Aufgabe? Stichworte genügen"
    }, {
      "type" : "textinput",
      "id" : "frage6"
    } ]
  }, {
    "actions" : [ "continue" ],
    "timelimit" : null,
    "items" : [ {
      "type" : "image",
      "path" : "1quadrate.jpg"
    }, {
      "type" : "textmessage",
      "content" : "Geben Sie die Lösung an."
    }, {
      "type" : "textinput",
      "id" : "frage7"
    } ]
  }, {
    "actions" : [ "continue" ],
    "timelimit" : null,
    "items" : [ {
      "type" : "textmessage",
      "content" : "logisch = ?"
    }, {
      "type" : "image",
      "path" : "2abcschlüssel.jpg"
    }, {
      "type" : "textmessage",
      "content" : "Geben Sie die Lösung an."
    }, {
      "type" : "textinput",
      "id" : "frage8"
    } ]
  }, {
    "actions" : [ "continue" ],
    "timelimit" : null,
    "items" : [ {
      "type" : "image",
      "path" : "3zahlenschlüssel.jpg"
    }, {
      "type" : "textmessage",
      "content" : "Geben Sie die Lösung zu 8 an."
    }, {
      "type" : "textinput",
      "id" : "frage9"
    } ]
  }, {
    "actions" : [ "continue" ],
    "timelimit" : null,
    "items" : [ {
      "type" : "textmessage",
      "content" : "Arbeitsplatz / Zunge / Elefant / ?"
    }, {
      "type" : "textinput",
      "id" : "frage10"
    } ]
  }, {
    "actions" : [ "continue" ],
    "timelimit" : null,
    "items" : [ {
      "type" : "image",
      "path" : "4elephant.jpg"
    }, {
      "type" : "textmessage",
      "content" : "Geben Sie die Lösung an."
    }, {
      "type" : "textinput",
      "id" : "frage11"
    } ]
  }, {
    "actions" : [ ],
    "timelimit" : {
      "group" : "",
      "seconds" : 5,
      "timeoutnotice" : true
    },
    "items" : [ {
      "type" : "textmessage",
      "content" : "Ich danke euch vielmals, dass ihr mitgemacht habt!"
    } ]
  } ]
}

