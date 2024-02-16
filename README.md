Para o desenvolvimento do projeto, foi necessário acessar o portal Azure, efetuar a criação de um recurso de serviço congnitivo em seguida eu acessei o portal vision e acessei a Featured "Detectar rostos em uma imagem" e em seguida efetuei o update da foto que contém o meu rosto,conforme imagem abaixo:

![foto do meu rosto](https://github.com/elvis1701/Lab-IA-ReconhecimentoFacial/assets/68926559/0dc3ee87-8b6c-4057-a139-c3656bd41c43)

Esses foram os resultados:

RECONHECIMENTO FACIAL:

Detected Atributes:

Face #1
Face mask: no

JSON

[
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 197,
      "height": 263,
      "left": 219,
      "top": 98
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 257.7,
        "y": 208.6
      },
      "pupilRight": {
        "x": 341.4,
        "y": 196.5
      },
      "noseTip": {
        "x": 289.8,
        "y": 244.9
      },
      "mouthLeft": {
        "x": 272.3,
        "y": 301.9
      },
      "mouthRight": {
        "x": 340.8,
        "y": 293.3
      },
      "eyebrowLeftOuter": {
        "x": 232.5,
        "y": 191.8
      },
      "eyebrowLeftInner": {
        "x": 271.6,
        "y": 183.8
      },
      "eyeLeftOuter": {
        "x": 244.2,
        "y": 211.7
      },
      "eyeLeftTop": {
        "x": 258.1,
        "y": 203.5
      },
      "eyeLeftBottom": {
        "x": 256.3,
        "y": 212.3
      },
      "eyeLeftInner": {
        "x": 272.2,
        "y": 206.8
      },
      "eyebrowRightInner": {
        "x": 311.9,
        "y": 178.6
      },
      "eyebrowRightOuter": {
        "x": 367.8,
        "y": 179.4
      },
      "eyeRightInner": {
        "x": 326.6,
        "y": 199.2
      },
      "eyeRightTop": {
        "x": 338.7,
        "y": 191.4
      },
      "eyeRightBottom": {
        "x": 342.4,
        "y": 200.2
      },
      "eyeRightOuter": {
        "x": 357.8,
        "y": 195.4
      },
      "noseRootLeft": {
        "x": 282.8,
        "y": 208
      },
      "noseRootRight": {
        "x": 306.7,
        "y": 203.3
      },
      "noseLeftAlarTop": {
        "x": 276.6,
        "y": 238.4
      },
      "noseRightAlarTop": {
        "x": 315.8,
        "y": 232.9
      },
      "noseLeftAlarOutTip": {
        "x": 272.5,
        "y": 257.7
      },
      "noseRightAlarOutTip": {
        "x": 326,
        "y": 252.4
      },
      "upperLipTop": {
        "x": 302.2,
        "y": 289.7
      },
      "upperLipBottom": {
        "x": 301.4,
        "y": 295.5
      },
      "underLipTop": {
        "x": 301.4,
        "y": 298
      },
      "underLipBottom": {
        "x": 302.7,
        "y": 306.3
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  }
]

Em seguida, selecionei a opção "Optical character recognition" e em seguida a Extraia texto de Imagens.
Efetuei a busca de uma foto que contenha textos como o exemplo da imagem abaixo, para realizar a análise:

![memoria ram](https://github.com/elvis1701/Lab-IA-ReconhecimentoFacial/assets/68926559/c42844ec-630c-42be-8b60-f06fc65301d3)

Esses foram os resultados:


Detected Atributes:

Face #1
Face mask: no

JSON

[
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 197,
      "height": 263,
      "left": 219,
      "top": 98
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 257.7,
        "y": 208.6
      },
      "pupilRight": {
        "x": 341.4,
        "y": 196.5
      },
      "noseTip": {
        "x": 289.8,
        "y": 244.9
      },
      "mouthLeft": {
        "x": 272.3,
        "y": 301.9
      },
      "mouthRight": {
        "x": 340.8,
        "y": 293.3
      },
      "eyebrowLeftOuter": {
        "x": 232.5,
        "y": 191.8
      },
      "eyebrowLeftInner": {
        "x": 271.6,
        "y": 183.8
      },
      "eyeLeftOuter": {
        "x": 244.2,
        "y": 211.7
      },
      "eyeLeftTop": {
        "x": 258.1,
        "y": 203.5
      },
      "eyeLeftBottom": {
        "x": 256.3,
        "y": 212.3
      },
      "eyeLeftInner": {
        "x": 272.2,
        "y": 206.8
      },
      "eyebrowRightInner": {
        "x": 311.9,
        "y": 178.6
      },
      "eyebrowRightOuter": {
        "x": 367.8,
        "y": 179.4
      },
      "eyeRightInner": {
        "x": 326.6,
        "y": 199.2
      },
      "eyeRightTop": {
        "x": 338.7,
        "y": 191.4
      },
      "eyeRightBottom": {
        "x": 342.4,
        "y": 200.2
      },
      "eyeRightOuter": {
        "x": 357.8,
        "y": 195.4
      },
      "noseRootLeft": {
        "x": 282.8,
        "y": 208
      },
      "noseRootRight": {
        "x": 306.7,
        "y": 203.3
      },
      "noseLeftAlarTop": {
        "x": 276.6,
        "y": 238.4
      },
      "noseRightAlarTop": {
        "x": 315.8,
        "y": 232.9
      },
      "noseLeftAlarOutTip": {
        "x": 272.5,
        "y": 257.7
      },
      "noseRightAlarOutTip": {
        "x": 326,
        "y": 252.4
      },
      "upperLipTop": {
        "x": 302.2,
        "y": 289.7
      },
      "upperLipBottom": {
        "x": 301.4,
        "y": 295.5
      },
      "underLipTop": {
        "x": 301.4,
        "y": 298
      },
      "underLipBottom": {
        "x": 302.7,
        "y": 306.3
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  }
]

Detected Atributes

D157F0147FD137/D1275D117F0107FD9
PN:PM081600D3
SKU:32291
7908020911586
SN:1158619011321

JSON

[
  {
    "lines": [
      {
        "text": "D15 7 F 014 7 F D13 7 / D12 7 5 D11 7 F 010 7 F D9",
        "boundingPolygon": [
          {
            "x": 94,
            "y": 319
          },
          {
            "x": 597,
            "y": 318
          },
          {
            "x": 597,
            "y": 332
          },
          {
            "x": 94,
            "y": 333
          }
        ],
        "words": [
          {
            "text": "D15",
            "boundingPolygon": [
              {
                "x": 101,
                "y": 320
              },
              {
                "x": 124,
                "y": 320
              },
              {
                "x": 124,
                "y": 333
              },
              {
                "x": 101,
                "y": 333
              }
            ],
            "confidence": 0.47
          },
          {
            "text": "7",
            "boundingPolygon": [
              {
                "x": 143,
                "y": 319
              },
              {
                "x": 150,
                "y": 319
              },
              {
                "x": 150,
                "y": 333
              },
              {
                "x": 143,
                "y": 333
              }
            ],
            "confidence": 0.894
          },
          {
            "text": "F",
            "boundingPolygon": [
              {
                "x": 157,
                "y": 319
              },
              {
                "x": 164,
                "y": 319
              },
              {
                "x": 164,
                "y": 333
              },
              {
                "x": 157,
                "y": 333
              }
            ],
            "confidence": 0.683
          },
          {
            "text": "014",
            "boundingPolygon": [
              {
                "x": 179,
                "y": 319
              },
              {
                "x": 202,
                "y": 319
              },
              {
                "x": 202,
                "y": 333
              },
              {
                "x": 179,
                "y": 333
              }
            ],
            "confidence": 0.359
          },
          {
            "text": "7",
            "boundingPolygon": [
              {
                "x": 222,
                "y": 319
              },
              {
                "x": 229,
                "y": 319
              },
              {
                "x": 229,
                "y": 333
              },
              {
                "x": 221,
                "y": 333
              }
            ],
            "confidence": 0.999
          },
          {
            "text": "F",
            "boundingPolygon": [
              {
                "x": 235,
                "y": 319
              },
              {
                "x": 243,
                "y": 319
              },
              {
                "x": 242,
                "y": 333
              },
              {
                "x": 235,
                "y": 333
              }
            ],
            "confidence": 0.997
          },
          {
            "text": "D13",
            "boundingPolygon": [
              {
                "x": 257,
                "y": 319
              },
              {
                "x": 280,
                "y": 319
              },
              {
                "x": 280,
                "y": 333
              },
              {
                "x": 256,
                "y": 333
              }
            ],
            "confidence": 0.608
          },
          {
            "text": "7",
            "boundingPolygon": [
              {
                "x": 299,
                "y": 319
              },
              {
                "x": 306,
                "y": 319
              },
              {
                "x": 306,
                "y": 333
              },
              {
                "x": 299,
                "y": 333
              }
            ],
            "confidence": 0.821
          },
          {
            "text": "/",
            "boundingPolygon": [
              {
                "x": 313,
                "y": 319
              },
              {
                "x": 320,
                "y": 319
              },
              {
                "x": 320,
                "y": 333
              },
              {
                "x": 313,
                "y": 333
              }
            ],
            "confidence": 0.243
          },
          {
            "text": "D12",
            "boundingPolygon": [
              {
                "x": 335,
                "y": 319
              },
              {
                "x": 358,
                "y": 319
              },
              {
                "x": 358,
                "y": 333
              },
              {
                "x": 335,
                "y": 333
              }
            ],
            "confidence": 0.411
          },
          {
            "text": "7",
            "boundingPolygon": [
              {
                "x": 377,
                "y": 319
              },
              {
                "x": 384,
                "y": 319
              },
              {
                "x": 383,
                "y": 333
              },
              {
                "x": 376,
                "y": 333
              }
            ],
            "confidence": 0.999
          },
          {
            "text": "5",
            "boundingPolygon": [
              {
                "x": 404,
                "y": 319
              },
              {
                "x": 412,
                "y": 319
              },
              {
                "x": 411,
                "y": 333
              },
              {
                "x": 404,
                "y": 333
              }
            ],
            "confidence": 0.457
          },
          {
            "text": "D11",
            "boundingPolygon": [
              {
                "x": 426,
                "y": 319
              },
              {
                "x": 449,
                "y": 319
              },
              {
                "x": 449,
                "y": 333
              },
              {
                "x": 425,
                "y": 333
              }
            ],
            "confidence": 0.379
          },
          {
            "text": "7",
            "boundingPolygon": [
              {
                "x": 468,
                "y": 319
              },
              {
                "x": 475,
                "y": 319
              },
              {
                "x": 475,
                "y": 333
              },
              {
                "x": 468,
                "y": 333
              }
            ],
            "confidence": 1
          },
          {
            "text": "F",
            "boundingPolygon": [
              {
                "x": 482,
                "y": 319
              },
              {
                "x": 489,
                "y": 319
              },
              {
                "x": 489,
                "y": 333
              },
              {
                "x": 482,
                "y": 333
              }
            ],
            "confidence": 0.993
          },
          {
            "text": "010",
            "boundingPolygon": [
              {
                "x": 504,
                "y": 319
              },
              {
                "x": 526,
                "y": 319
              },
              {
                "x": 526,
                "y": 333
              },
              {
                "x": 504,
                "y": 333
              }
            ],
            "confidence": 0.234
          },
          {
            "text": "7",
            "boundingPolygon": [
              {
                "x": 546,
                "y": 319
              },
              {
                "x": 553,
                "y": 319
              },
              {
                "x": 552,
                "y": 333
              },
              {
                "x": 545,
                "y": 333
              }
            ],
            "confidence": 0.999
          },
          {
            "text": "F",
            "boundingPolygon": [
              {
                "x": 560,
                "y": 319
              },
              {
                "x": 567,
                "y": 319
              },
              {
                "x": 566,
                "y": 333
              },
              {
                "x": 559,
                "y": 333
              }
            ],
            "confidence": 0.67
          },
          {
            "text": "D9",
            "boundingPolygon": [
              {
                "x": 582,
                "y": 319
              },
              {
                "x": 597,
                "y": 319
              },
              {
                "x": 597,
                "y": 333
              },
              {
                "x": 581,
                "y": 333
              }
            ],
            "confidence": 0.749
          }
        ]
      },
      {
        "text": "PN:PM081600D3",
        "boundingPolygon": [
          {
            "x": 209,
            "y": 354
          },
          {
            "x": 291,
            "y": 356
          },
          {
            "x": 291,
            "y": 366
          },
          {
            "x": 209,
            "y": 365
          }
        ],
        "words": [
          {
            "text": "PN:PM081600D3",
            "boundingPolygon": [
              {
                "x": 210,
                "y": 355
              },
              {
                "x": 290,
                "y": 356
              },
              {
                "x": 290,
                "y": 366
              },
              {
                "x": 209,
                "y": 365
              }
            ],
            "confidence": 0.803
          }
        ]
      },
      {
        "text": "SKU:32291",
        "boundingPolygon": [
          {
            "x": 209,
            "y": 368
          },
          {
            "x": 262,
            "y": 368
          },
          {
            "x": 262,
            "y": 378
          },
          {
            "x": 209,
            "y": 378
          }
        ],
        "words": [
          {
            "text": "SKU:32291",
            "boundingPolygon": [
              {
                "x": 210,
                "y": 368
              },
              {
                "x": 262,
                "y": 369
              },
              {
                "x": 262,
                "y": 379
              },
              {
                "x": 210,
                "y": 379
              }
            ],
            "confidence": 0.877
          }
        ]
      },
      {
        "text": "7 908020 911586",
        "boundingPolygon": [
          {
            "x": 104,
            "y": 386
          },
          {
            "x": 197,
            "y": 387
          },
          {
            "x": 197,
            "y": 398
          },
          {
            "x": 104,
            "y": 397
          }
        ],
        "words": [
          {
            "text": "7",
            "boundingPolygon": [
              {
                "x": 105,
                "y": 386
              },
              {
                "x": 110,
                "y": 387
              },
              {
                "x": 110,
                "y": 397
              },
              {
                "x": 104,
                "y": 397
              }
            ],
            "confidence": 0.986
          },
          {
            "text": "908020",
            "boundingPolygon": [
              {
                "x": 116,
                "y": 387
              },
              {
                "x": 152,
                "y": 389
              },
              {
                "x": 151,
                "y": 398
              },
              {
                "x": 115,
                "y": 397
              }
            ],
            "confidence": 0.994
          },
          {
            "text": "911586",
            "boundingPolygon": [
              {
                "x": 157,
                "y": 389
              },
              {
                "x": 193,
                "y": 389
              },
              {
                "x": 192,
                "y": 397
              },
              {
                "x": 156,
                "y": 398
              }
            ],
            "confidence": 0.989
          }
        ]
      },
      {
        "text": "SN:1158619011321",
        "boundingPolygon": [
          {
            "x": 207,
            "y": 379
          },
          {
            "x": 302,
            "y": 379
          },
          {
            "x": 302,
            "y": 390
          },
          {
            "x": 207,
            "y": 390
          }
        ],
        "words": [
          {
            "text": "SN:1158619011321",
            "boundingPolygon": [
              {
                "x": 209,
                "y": 380
              },
              {
                "x": 302,
                "y": 380
              },
              {
                "x": 302,
                "y": 391
              },
              {
                "x": 209,
                "y": 390
              }
            ],
            "confidence": 0.861
          }
        ]
      }
    ]
  }
]
