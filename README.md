# Ukrainian Top 1000 Words with Audio Files 

This repository contains the data that has been used
to create the [Ukrainian Top 1000 Words course][ukr-memrise-course]
on memrise.

## Content

The JSON file `ukrcourse.json` contains an array of datasets where each dataset
contains the fields:

- `Ukrainian`: Ukrainian word
- `English`: English translation
- `Wordinfo`: Grammatical information of the word
- `audiofiles`: An array with the names of the audio files that contain the pronunciation

The audiofiles are in `mp3` format and can be found in the `audiofiles` directory.

## Sources

The datasets were assembled based on information available at: 

- Word frequency list: <http://u-mova.blogspot.com/2013/09/blog-post.html> ([CC-BY-SA 3.0])   
- Majority of English translations: <https://app.memrise.com/course/772935/ukrainian-20k-words-ordered-by-frequency/> 
- Dictionary with grammar information: <http://www.sum.in.ua/>
- Audio files: <https://shtooka.net/>

Some words were deleted from the word frequency list if their meaning was too ambiguous.
Some translations were modified or improved using freely available online dictionaries.

[ukr-memrise-course]: https://app.memrise.com/course/927442/ukrainian-top-1000-words-audio/
[CC-BY-SA 3.0]: https://creativecommons.org/licenses/by-sa/3.0/deed.en

# License

This material is licensed under the Creative Commons [CC-BY-SA 4.0] license.

[CC-BY-SA 4.0]: https://creativecommons.org/licenses/by-sa/4.0/deed.en

