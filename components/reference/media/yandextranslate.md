# YandexTranslate

Use this component to translate words and sentences between different languages. This component needs Internet access, as it will request translations to the Yandex.Translate service. Specify the source and target language in the form source-target using two letter language codes. So "en-es" will translate from English to Spanish while "es-ru" will translate from Spanish to Russian. If you leave out the source language, the service will attempt to detect the source language. So providing just "es" will attempt to detect the source language and translate it to Spanish. This component is powered by the Yandex translation service. See [http://api.yandex.com/translate/](http://api.yandex.com/translate/) for more information, including the list of available languages and the meanings of the language codes and status codes. Note: Translation happens asynchronously in the background. When the translation is complete, the "GotTranslation" event is triggered.

## Properties

### ApiKey

## Events

### GotTranslation

| Parameter | Type |
| :--- | :--- |
| responseCode | text |
| translation | text |

Event triggered when the Yandex.Translate service returns the translated text. This event also provides a response code for error handling. If the responseCode is not 200, then something went wrong with the call, and the translation will not be available.

## Methods

### RequestTranslation

| Parameter | Type |
| :--- | :--- |
| languageToTranslateTo | text |
| textToTranslate | text |

By providing a target language to translate to \(for instance, 'es' for Spanish, 'en' for English, or 'ru' for Russian\), and a word or sentence to translate, this method will request a translation to the Yandex.Translate service. Once the text is translated by the external service, the event GotTranslation will be executed.

Note: Yandex.Translate will attempt to detect the source language. You can also specify prepending it to the language translation, i.e., "es-ru" will specify Spanish to Russian translation.

