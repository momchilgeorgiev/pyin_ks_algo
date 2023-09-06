Here I describe how the data for the project has been gathered. I also describe how and where to download the data, also how everything *should* look in the end 

=-------------------------------------------------------------------------------------------------------------------------------------------=

For this project I have went with Music net: 
https://www.kaggle.com/datasets/imsparsh/musicnet-dataset?select=musicnet_metadata.csv

The dataset is 20gb+ in size and contains .wavs and optionally midis. When you download it you will see the following dirs:

../musicnet/test_data
../musicnet/test_data_labels
../musicnet/train_data
../musicnet/train_data_labels

The train_data is the largest set, about 20gb, test data is around 200mb. In the testing I have used the **/train_data**. If you choose to not download it I have saved all the data gathered in `../test_results`, which contains `/csv` and `/graphs`:

`/csv` - csv files gathered during testing of the algorithms
`/graphs` - the graphs from the csv files

Keep in mind if you download only `/test_data` the results will be different. From the provided kaggle post you can also download `musicnet_metadata.csv`, which contains the information for all the .wavs. It should be downloaded and put as:

../musicnet/musicnet_metadata.csv

I have also used other audio samples recorded directly by me or taken from my DAW (Ableton). They are located in `./Project_PDA/audio/testing`. Here is the link to that also just in case:
https://kaggle.com/datasets/669237b7c1042c5901ff21f5e6c68b6f695f6d50bba2784788b64a6db35f4c41

If you download it you will see the following dir:

../audio/testing

When everything is downloaded you should have the following directory structure:

./Project_PDA/audio
./Project_PDA/main
./Project_PDA/media
./Project_PDA/musicnet
./Project_PDA/outputs
./Project_PDA/test_results
./Project_PDA/readme.md

=-------------------------------------------------------------------------------------------------------------------------------------------=
