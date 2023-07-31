# Spoiler-Detection

Entertainment is an important part of all our lives and movie shows & TV series account for a huge percent of entertainment across the globe. Nobody would want the experience of watching an interesting movie/series to be spoiled beforehand. Thus, __spoilers have to be avoided before watching any film__. 

A spoiler is defined as a remark or piece of information which __reveals important plot elements__ (for example the ending or a major plot twist), thus 'spoiling' a surprise and robbing the viewer of the suspense and enjoyment of the film. 

Spoiler detector intends to __spot any line in a text which can be perceived as a spoiler__ for a movie/series that the user provides and hide those reviews so that the user can enjoy the film in its full essence in near future. 

We have implemented the __BERT and LSTM model__ for this purpose and the highest __AUC score__ obtained was approximately __0.84__, from the LSTM model. Our BERT model has subpar performance, having AUC close to __0.5__. 

It has a scope in text detection in an image as well. Spoilers are not restricted to text reviews but they’re given to users in the form of memes and posts as well. Later on, the machine can be trained to identify ‘spoiler words’ within an image and hide it for the user. 
