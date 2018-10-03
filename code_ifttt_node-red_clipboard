[
    {
        "id": "406517ac.a01d78",
        "type": "tab",
        "label": "Flow 1",
        "disabled": false,
        "info": ""
    },
    {
        "id": "4027ab22.7a6ad4",
        "type": "http in",
        "z": "406517ac.a01d78",
        "name": "ON",
        "url": "/incoming1",
        "method": "post",
        "upload": true,
        "swaggerDoc": "",
        "x": 190,
        "y": 220,
        "wires": [
            [
                "69c05368.a566bc",
                "65009514.b64e8c"
            ]
        ]
    },
    {
        "id": "69c05368.a566bc",
        "type": "http response",
        "z": "406517ac.a01d78",
        "name": "HTTP OK",
        "statusCode": "",
        "headers": {},
        "x": 580,
        "y": 200,
        "wires": []
    },
    {
        "id": "37bae427.b5a7ac",
        "type": "rpi-gpio out",
        "z": "406517ac.a01d78",
        "name": "Relay 1",
        "pin": "29",
        "set": true,
        "level": "1",
        "freq": "",
        "out": "out",
        "x": 980,
        "y": 300,
        "wires": []
    },
    {
        "id": "488522f6.2c9f5c",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "1",
        "op2": "0",
        "op1type": "str",
        "op2type": "str",
        "duration": "0",
        "extend": false,
        "units": "ms",
        "reset": "ON",
        "bytopic": "all",
        "name": "OFF",
        "x": 790,
        "y": 280,
        "wires": [
            [
                "37bae427.b5a7ac"
            ]
        ]
    },
    {
        "id": "c0c18564.db4fb8",
        "type": "http in",
        "z": "406517ac.a01d78",
        "name": "OFF",
        "url": "/incoming2",
        "method": "post",
        "upload": false,
        "swaggerDoc": "",
        "x": 190,
        "y": 280,
        "wires": [
            [
                "69c05368.a566bc",
                "f4152443.1adc48"
            ]
        ]
    },
    {
        "id": "179434c8.015f7b",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "0",
        "op2": "0",
        "op1type": "str",
        "op2type": "str",
        "duration": "0",
        "extend": false,
        "units": "ms",
        "reset": "OFF",
        "bytopic": "all",
        "name": "ON",
        "x": 790,
        "y": 340,
        "wires": [
            [
                "37bae427.b5a7ac"
            ]
        ]
    },
    {
        "id": "f4152443.1adc48",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "ON",
        "op2": "OFF",
        "op1type": "str",
        "op2type": "str",
        "duration": "1",
        "extend": false,
        "units": "ms",
        "reset": "",
        "bytopic": "all",
        "name": "",
        "x": 590,
        "y": 360,
        "wires": [
            [
                "488522f6.2c9f5c",
                "179434c8.015f7b"
            ]
        ]
    },
    {
        "id": "65009514.b64e8c",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "OFF",
        "op2": "ON",
        "op1type": "str",
        "op2type": "str",
        "duration": "1",
        "extend": false,
        "units": "ms",
        "reset": "",
        "bytopic": "all",
        "name": "",
        "x": 590,
        "y": 280,
        "wires": [
            [
                "488522f6.2c9f5c",
                "179434c8.015f7b"
            ]
        ]
    },
    {
        "id": "bc628e14.7bec6",
        "type": "inject",
        "z": "406517ac.a01d78",
        "name": "ON",
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "x": 170,
        "y": 100,
        "wires": [
            [
                "65009514.b64e8c"
            ]
        ]
    },
    {
        "id": "725eb185.d2015",
        "type": "inject",
        "z": "406517ac.a01d78",
        "name": "OFF",
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "x": 170,
        "y": 160,
        "wires": [
            [
                "f4152443.1adc48"
            ]
        ]
    },
    {
        "id": "8f0381cf.f795b",
        "type": "http in",
        "z": "406517ac.a01d78",
        "name": "ON",
        "url": "/incoming3",
        "method": "post",
        "upload": true,
        "swaggerDoc": "",
        "x": 210,
        "y": 540,
        "wires": [
            [
                "c41824f2.990f68",
                "61571e4e.71faa"
            ]
        ]
    },
    {
        "id": "c41824f2.990f68",
        "type": "http response",
        "z": "406517ac.a01d78",
        "name": "HTTP OK",
        "statusCode": "",
        "headers": {},
        "x": 600,
        "y": 520,
        "wires": []
    },
    {
        "id": "c53ea71b.e63568",
        "type": "rpi-gpio out",
        "z": "406517ac.a01d78",
        "name": "Relay 2",
        "pin": "31",
        "set": true,
        "level": "1",
        "freq": "",
        "out": "out",
        "x": 1000,
        "y": 620,
        "wires": []
    },
    {
        "id": "a9a46dd6.9ea9",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "1",
        "op2": "0",
        "op1type": "str",
        "op2type": "str",
        "duration": "0",
        "extend": false,
        "units": "ms",
        "reset": "ON",
        "bytopic": "all",
        "name": "OFF",
        "x": 810,
        "y": 600,
        "wires": [
            [
                "c53ea71b.e63568"
            ]
        ]
    },
    {
        "id": "30bce9ab.8a1636",
        "type": "http in",
        "z": "406517ac.a01d78",
        "name": "OFF",
        "url": "/incoming4",
        "method": "post",
        "upload": false,
        "swaggerDoc": "",
        "x": 210,
        "y": 600,
        "wires": [
            [
                "c41824f2.990f68",
                "838960aa.c041c"
            ]
        ]
    },
    {
        "id": "f4ef21ab.5f177",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "0",
        "op2": "0",
        "op1type": "str",
        "op2type": "str",
        "duration": "0",
        "extend": false,
        "units": "ms",
        "reset": "OFF",
        "bytopic": "all",
        "name": "ON",
        "x": 810,
        "y": 660,
        "wires": [
            [
                "c53ea71b.e63568"
            ]
        ]
    },
    {
        "id": "838960aa.c041c",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "ON",
        "op2": "OFF",
        "op1type": "str",
        "op2type": "str",
        "duration": "1",
        "extend": false,
        "units": "ms",
        "reset": "",
        "bytopic": "all",
        "name": "",
        "x": 610,
        "y": 680,
        "wires": [
            [
                "a9a46dd6.9ea9",
                "f4ef21ab.5f177"
            ]
        ]
    },
    {
        "id": "61571e4e.71faa",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "OFF",
        "op2": "ON",
        "op1type": "str",
        "op2type": "str",
        "duration": "1",
        "extend": false,
        "units": "ms",
        "reset": "",
        "bytopic": "all",
        "name": "",
        "x": 610,
        "y": 600,
        "wires": [
            [
                "a9a46dd6.9ea9",
                "f4ef21ab.5f177"
            ]
        ]
    },
    {
        "id": "e772046a.3f48d8",
        "type": "inject",
        "z": "406517ac.a01d78",
        "name": "ON",
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "x": 190,
        "y": 420,
        "wires": [
            [
                "61571e4e.71faa"
            ]
        ]
    },
    {
        "id": "4366eae1.9aab14",
        "type": "inject",
        "z": "406517ac.a01d78",
        "name": "OFF",
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "x": 190,
        "y": 480,
        "wires": [
            [
                "838960aa.c041c"
            ]
        ]
    },
    {
        "id": "477d481d.536cf8",
        "type": "http in",
        "z": "406517ac.a01d78",
        "name": "ON",
        "url": "/incoming5",
        "method": "post",
        "upload": true,
        "swaggerDoc": "",
        "x": 230,
        "y": 860,
        "wires": [
            [
                "8734d8fd.08bb38",
                "2439e75b.11cb98"
            ]
        ]
    },
    {
        "id": "8734d8fd.08bb38",
        "type": "http response",
        "z": "406517ac.a01d78",
        "name": "HTTP OK",
        "statusCode": "",
        "headers": {},
        "x": 620,
        "y": 840,
        "wires": []
    },
    {
        "id": "c7472703.094818",
        "type": "rpi-gpio out",
        "z": "406517ac.a01d78",
        "name": "Relay 3",
        "pin": "33",
        "set": true,
        "level": "1",
        "freq": "",
        "out": "out",
        "x": 1020,
        "y": 940,
        "wires": []
    },
    {
        "id": "e3dc3dce.09985",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "1",
        "op2": "0",
        "op1type": "str",
        "op2type": "str",
        "duration": "0",
        "extend": false,
        "units": "ms",
        "reset": "ON",
        "bytopic": "all",
        "name": "OFF",
        "x": 830,
        "y": 920,
        "wires": [
            [
                "c7472703.094818"
            ]
        ]
    },
    {
        "id": "2f0799e6.e9ca76",
        "type": "http in",
        "z": "406517ac.a01d78",
        "name": "OFF",
        "url": "/incoming6",
        "method": "post",
        "upload": false,
        "swaggerDoc": "",
        "x": 230,
        "y": 920,
        "wires": [
            [
                "8734d8fd.08bb38",
                "7a9209f9.fd9048"
            ]
        ]
    },
    {
        "id": "aa3a9ac2.225648",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "0",
        "op2": "0",
        "op1type": "str",
        "op2type": "str",
        "duration": "0",
        "extend": false,
        "units": "ms",
        "reset": "OFF",
        "bytopic": "all",
        "name": "ON",
        "x": 830,
        "y": 980,
        "wires": [
            [
                "c7472703.094818"
            ]
        ]
    },
    {
        "id": "7a9209f9.fd9048",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "ON",
        "op2": "OFF",
        "op1type": "str",
        "op2type": "str",
        "duration": "1",
        "extend": false,
        "units": "ms",
        "reset": "",
        "bytopic": "all",
        "name": "",
        "x": 630,
        "y": 1000,
        "wires": [
            [
                "e3dc3dce.09985",
                "aa3a9ac2.225648"
            ]
        ]
    },
    {
        "id": "2439e75b.11cb98",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "OFF",
        "op2": "ON",
        "op1type": "str",
        "op2type": "str",
        "duration": "1",
        "extend": false,
        "units": "ms",
        "reset": "",
        "bytopic": "all",
        "name": "",
        "x": 630,
        "y": 920,
        "wires": [
            [
                "e3dc3dce.09985",
                "aa3a9ac2.225648"
            ]
        ]
    },
    {
        "id": "7c4b0a64.e7b2b4",
        "type": "inject",
        "z": "406517ac.a01d78",
        "name": "ON",
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "x": 210,
        "y": 740,
        "wires": [
            [
                "2439e75b.11cb98"
            ]
        ]
    },
    {
        "id": "8e9f3871.e8f148",
        "type": "inject",
        "z": "406517ac.a01d78",
        "name": "OFF",
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "x": 210,
        "y": 800,
        "wires": [
            [
                "7a9209f9.fd9048"
            ]
        ]
    },
    {
        "id": "b67c14c2.1f0418",
        "type": "http in",
        "z": "406517ac.a01d78",
        "name": "ON",
        "url": "/incoming7",
        "method": "post",
        "upload": true,
        "swaggerDoc": "",
        "x": 250,
        "y": 1200,
        "wires": [
            [
                "1d41411d.fec52f",
                "fb69313e.c49b6"
            ]
        ]
    },
    {
        "id": "1d41411d.fec52f",
        "type": "http response",
        "z": "406517ac.a01d78",
        "name": "HTTP OK",
        "statusCode": "",
        "headers": {},
        "x": 640,
        "y": 1180,
        "wires": []
    },
    {
        "id": "aa09f746.a0b6d8",
        "type": "rpi-gpio out",
        "z": "406517ac.a01d78",
        "name": "Relay 4",
        "pin": "35",
        "set": true,
        "level": "1",
        "freq": "",
        "out": "out",
        "x": 1040,
        "y": 1280,
        "wires": []
    },
    {
        "id": "68876eaa.7b3c",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "1",
        "op2": "0",
        "op1type": "str",
        "op2type": "str",
        "duration": "0",
        "extend": false,
        "units": "ms",
        "reset": "ON",
        "bytopic": "all",
        "name": "OFF",
        "x": 850,
        "y": 1260,
        "wires": [
            [
                "aa09f746.a0b6d8"
            ]
        ]
    },
    {
        "id": "17fb90af.97539f",
        "type": "http in",
        "z": "406517ac.a01d78",
        "name": "OFF",
        "url": "/incoming8",
        "method": "post",
        "upload": false,
        "swaggerDoc": "",
        "x": 250,
        "y": 1260,
        "wires": [
            [
                "1d41411d.fec52f",
                "a72d10e1.0b42"
            ]
        ]
    },
    {
        "id": "4d148d41.6381c4",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "0",
        "op2": "0",
        "op1type": "str",
        "op2type": "str",
        "duration": "0",
        "extend": false,
        "units": "ms",
        "reset": "OFF",
        "bytopic": "all",
        "name": "ON",
        "x": 850,
        "y": 1320,
        "wires": [
            [
                "aa09f746.a0b6d8"
            ]
        ]
    },
    {
        "id": "a72d10e1.0b42",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "ON",
        "op2": "OFF",
        "op1type": "str",
        "op2type": "str",
        "duration": "1",
        "extend": false,
        "units": "ms",
        "reset": "",
        "bytopic": "all",
        "name": "",
        "x": 650,
        "y": 1340,
        "wires": [
            [
                "68876eaa.7b3c",
                "4d148d41.6381c4"
            ]
        ]
    },
    {
        "id": "fb69313e.c49b6",
        "type": "trigger",
        "z": "406517ac.a01d78",
        "op1": "OFF",
        "op2": "ON",
        "op1type": "str",
        "op2type": "str",
        "duration": "1",
        "extend": false,
        "units": "ms",
        "reset": "",
        "bytopic": "all",
        "name": "",
        "x": 650,
        "y": 1260,
        "wires": [
            [
                "68876eaa.7b3c",
                "4d148d41.6381c4"
            ]
        ]
    },
    {
        "id": "493b67e9.85b908",
        "type": "inject",
        "z": "406517ac.a01d78",
        "name": "ON",
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "x": 230,
        "y": 1080,
        "wires": [
            [
                "fb69313e.c49b6"
            ]
        ]
    },
    {
        "id": "fb1470a4.62844",
        "type": "inject",
        "z": "406517ac.a01d78",
        "name": "OFF",
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "x": 230,
        "y": 1140,
        "wires": [
            [
                "a72d10e1.0b42"
            ]
        ]
    }
]
