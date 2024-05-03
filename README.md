### Preparation

1. Utwórz plik `speech-to-text-eagi/service_account_file.json` i zapisz w nim klucz dostepu do google cloud api z 
włączonym Speech-To-Text API.
EN-1. Create a file speech-to-text-eagi/service_account_file.json and save the access key to the Google Cloud API with Speech-To-Text API enabled in it.

2. Utwórz plik `src/service_account_file.json` i zapisz w nim klucz dostepu do google cloud api z 
włączonym Text-To-Speech API.
EN-2. Create a file src/service_account_file.json and save the access key to the Google Cloud API with Text-To-Speech API enabled in it.

3. Uruchom `docker-compose up`.
EN-3. Run docker-compose up.

4. Połącz się klientem SIP na udp localhost:5060 – username i password 6001.
EN-4. Connect with SIP client to udp localhost:5060 – username i and password 6001.

5. Zadzwoń na numer 5000.
EN-5. Call 5000.

### Setup Flotiq

Utworz konto [Flotiq](https://flotiq.com) i pobierz klucz API.

### Maintainers

Maintained by [CodeWave](https://codewave.eu)
