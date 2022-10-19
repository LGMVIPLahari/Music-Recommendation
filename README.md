# Music-Recommendation
MUSIC RECOMMENDATION SYSTEM -- CONTENT-BASED-APPROACH
Dataset from : https://www.kaggle.com/c/kkbox-music-recommendation-challenge/data
Files Used:
    a) train.csv          -->  Used Attributes: msno(user_id), song_id
    b) song.csv           -->  Used Attributes: song_id, genre_ids, artist_name, composer, lyricist
    c) song_info.csv      -->  Used Attributes:  song_id, name(song_name)
○ Merging above tables with mentioned attributes, DataFrame main_df is created.

○ Appending corresponding values of genre_ids, artist_name, composer & lyricist , new attribute song_details is created which is used for the calculation of Cosine Similarities

STEPS :
1) Importing Libraries and Loading datasets
2) Exploratoty Data Analysis(EDA) & Visualization -- BarDiagram of Top 7 : Genre_IDs vs their Frequency
3) Data Preprocessing & Preparing Main datasets.
4) Computing Similarities betn Songs using Cosine_similarities.
5) Constructing Content Based Recommendation System.
6) Making Recommendation of Songs to Users.
7) Acknowledgement and References
