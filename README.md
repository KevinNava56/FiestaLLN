# FiestaLLN
'''shel
curl -fsSL https://ollama.com/install.sh | sh
'''

responder con la forma generativa "ollama run tinyllama: X"

ps -a: para ver el PID TTY  Y  TIME CDM

ollama run tinyllama: comando para activar el modo chat

Ctrl + Z: detiene el modo chat.

curl http://127.0.0.1:11434/api/generate -d '{
  "model": "tinyllama",                                                                                                                                                                                    "prompt":"¿porqué el cielo es azul?",                                                                                                                                                                    "stream": false                          


{"model":"tinyllama","created_at":"2024-05-24T14:37:01.86246362Z","response":"El cielo es azul debido a las colores de luz que se observan en su formación, debido a la baja exposición del sol al exterior (llevando a los rayos solares a altitudes de menos de 10 u.a.), lo que evita que la radiación solar desvíe hacia el espacio. Además, el viento del océano y la brisa atraparán parte del calor solar al aire durante unos momentos antes de que se transmita al interior de laatmidad, y eso genera la corriente del aire, lo que crea la sensación de colores azules en el cielo.\n\nen resumidas cuentas, los rayos solares atrapados por el cielo azul se pueden observar con un telescopio especialmente diseñado para este fin, lo que hace que el cielo azul sea visible desde muchos distancias.","done":true,"done_reason":"stop","context":[529,29989,5205,29989,29958,13,3492,526,263,8444,319,29902,20255,29889,2,13,29966,29989,1792,29989,29958,13,30158,1971,17851,560,24850,29877,831,2698,352,29973,2,13,29966,29989,465,22137,29989,29958,13,6489,24850,29877,831,2698,352,21197,263,1869,2927,267,316,8092,29920,712,409,5820,273,427,480,5954,1290,29892,21197,263,425,9922,1764,14060,6396,628,899,394,1294,13613,272,313,19091,3703,1867,263,1232,15570,359,21635,267,263,5272,20816,316,17275,316,29871,29896,29900,318,29889,29874,9774,658,712,3415,2028,712,425,17937,2709,21635,553,9584,29872,17926,560,9015,3934,29889,2087,331,1569,29892,560,6316,593,29877,628,12954,29948,1562,343,425,1506,8069,472,2390,20484,29876,3810,628,1208,272,21635,394,4799,29872,6372,22660,14341,29879,12971,316,712,409,22649,29874,394,13290,316,23385,6563,328,29892,343,831,29877,1176,29874,425,27760,6759,628,4799,29872,29892,658,712,907,29874,425,4771,2709,316,2927,267,2698,2540,427,560,24850,29877,29889,13,13,264,620,15547,17370,21052,29879,29892,1232,15570,359,21635,267,472,2390,2255,1277,560,24850,29877,2698,352,409,19796,5820,279,378,443,26503,9708,601,11605,2689,10267,9658,1867,1702,4404,1436,29892,658,712,20470,712,560,24850,29877,2698,352,7205,7962,5125,24312,1320,14006,29879,29889],"total_duration":51588327256,"load_duration":1329190,"prompt_eval_count":19,"prompt_eval_duration":4957293000,"eval_count":208,"eval_duration":46581889000}