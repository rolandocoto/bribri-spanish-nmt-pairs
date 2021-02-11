# Pares de oraciones en bribri-español

El documento CSV contiene pares de oraciones en español y en la lengua chibcha bribri, hablada por aproximadamente 3000 personas en el sur de Costa Rica. Para usar estos datos por favor cite el siguiente artículo:

> Feldman, Isaac & Coto-Solano, Rolando (2020). Neural Machine Translation Models with Back-Translation for the Extremely Low-Resource Indigenous Language Bribri. CoLing.

El documento CSV contiene las siguientes columnas:

`id`: Número de la oración

`Source`: Oración en bribri. Las oraciones están en una transcripción especial para intentar uniformar las diferentes ortografías existentes. El documento `orthographic-conversion.csv` contiene detalles de cómo convertir la ortografía de entrenamiento a los dos estándares ortográficos existentes (basados en Constenla 1998 y Jara Murillo 2013).

`Target`: Oración en español

`Reference`: Fuente de la oración

`Orig-Nasal-As-Line`: Oración en la forma ortográfica original, si esta fue tomada de un libro que marque las vocales nasales con una línea debajo.

`Orig-Nasal-As-Tilde`: Oración en la forma ortográfica original, si esta fue tomada de un libro que marque las vocales nasales con una vírgula ("cola de la eñe").

# Bribri-Spanish Sentence Pairs

The CSV document contains pairs of sentences in Spanish and in the Chibchan language Bribri, spoken by approximately 3000 people in Southern Costa Rica. If you are going to use the data, please cite the following paper:

> Feldman, Isaac & Coto-Solano, Rolando (2020). Neural Machine Translation Models with Back-Translation for the Extremely Low-Resource Indigenous Language Bribri. CoLing.

The CSV file has the following columns:

`id`: Number of the sentence

`Source`: Sentence in Bribri. The sentences are in a special transcription format to try to create a uniform training set from the different orthographies in use. The document `orthographic-conversion.csv` has details of how to convert the training sentences to the two existing orthographic standards (based on Constenla 1998 y Jara Murillo 2013).

`Target`: Sentence in Spanish

`Reference`: Source of the sentence

`Orig-Nasal-As-Line`: Sentence in the original orthographic form, if the sentence was taken from a book that marks nasal vowels with a line underneath.

`Orig-Nasal-As-Tilde`: Sentence in the original orthographic form, if the sentence was taken from a book that marks nasal vowels with a tilde.

# Bribri-Spanish Sentence Pairs

The `.es` and `.bzd` files contain pairs of sentences in Spanish and in the [Chibchan language Bribri](https://en.wikipedia.org/wiki/Bribri_language), spoken by approximately 3000 people in Southern Costa Rica. If you are going to use the data, please cite the following paper:

> Feldman, I., & Coto-Solano, R. (2020, December). [_Neural Machine Translation Models with Back-Translation for the Extremely Low-Resource Indigenous Language Bribri_](https://www.aclweb.org/anthology/2020.coling-main.351/). In Proceedings of the 28th International Conference on Computational Linguistics (pp. 3965-3976).

The Bribri language has two major orthographies: the Constenla (1998) system, and the Jara (2013) system. Moreover, Bribri writing is not fully standardized, so there is considerable spelling variation between documents. In order to facilitate training, the sentences in the `.bzd` files use an intermediate representation of the orthography. This intermediate representation is meant for use by NLP algorithms; it unifies the existing orthographies but reduces the human readability of the text.

If you are going to use the Bribri sentences in print, please convert the intermediate form into a human-readable form first. You can do this by using the equivalences in `orthographic-conversion.csv`. You can also use the function `convertToSpelling` in the file `bribri-orthography-conversion.ipynb`.

The sentences in the `.bzd` files were compiled from the sources cited below.

Fuentes / Sources
------

`constenla1998`: Constenla Umaña, A.; Elizondo Figueroa, F.; Pereira Mora, F (1998). _Curso Básico de Bribri_. San José, Costa Rica: Editorial de la Universidad de Costa Rica.

`corpusSofía`: Flores Solórzano, Sofía (2017). _Corpus oral pandialectal de la lengua bribri_. URL http://bribri.net

`grammarJara`: Jara Murillo, Carla Victoria (2018). _Gramática de la lengua bribri_. San José, Costa Rica: EDigital. URL: https://www.lenguabribri.com/gram%C3%A1tica-de-la-lengua-bribri

`jaraAprendamos`: Jara Murillo, C.; García Segura, A (2013). _Se' ttö́ bribri ie - Hablemos en bribri_. San José: CONARE - Programa de Regionalización Interuniversitaria. URL: https://www.lenguabribri.com/se-tt%C3%B6-bribri-ie-hablemos-en-bribri.

`jara-itte`: Jara Murillo, Carla Victoria (1993). _I ttè - Historias bribris_. URL: https://www.lenguabribri.com/i-tt%C3%A8-historias-bribris

`margery`: Margery Peña, Enrique (2013). _Diccionario fraseológico Bribri-Español Español-Bribri_. San José, Costa Rica: Editorial de la Universidad de Costa Rica.
