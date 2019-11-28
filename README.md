# Predict-the-popularity-of-articles

La description des variables :

0. url : URL de l’article (non pertinent)  
1. timedelta : Jours entre la publication de l’article et l’acquisition du dataset   (non pertinent)  
2. n_tokens_Titre : Nombre de mots dans le titre   
3. n_tokens_content : Nombre de mots de l’article   
4. n_unique_tokens : Taux de mots uniques de l’article   
5. n_non_stop_mots : Taux de mots n’étant pas des stop‐words dans l’article   
6. n_non_stop_unique_tokens : Taux de mots uniques n’étant pas des stop‐words dans l’article  
7. num_hrefs : Nombre de liens   
8. num_self_hrefs : Nombre de liens à d’autres articles du même site  
9. num_imgs : Nombre d’images   
10. num_videos : Nombre de videos   
11. average_token_length : Longueur moyenne des mots dans l’article  
12. num_keywords : Nombre de mots‐clefs dans la metadata   
13. data_channel_is_lifestyle : Publié dans la rubrique 'Lifestyle'?   
14. data_channel_is_entertainment : Publié dans la rubrique 'Entertainment'?   
15. data_channel_is_bus : Publié dans la rubrique 'Business'?  
16. data_channel_is_socmed : Publié dans la rubrique 'Social Media'?   
17. data_channel_is_tech : Publié dans la rubrique 'Tech'?   
18. data_channel_is_world : Publié dans la rubrique 'World'?  
19. kw_min_min : Pire mot‐clef (min. partages)   
20. kw_max_min : Pire mot‐clef (max. partages)   
21. kw_avg_min : Pire mot‐clef (moy. partages)   
22. kw_min_max : Meilleur mot‐clef (min. partages)   
23. kw_max_max : Meilleur mot‐clef (max. partages)   
24. kw_avg_max : Meilleur mot‐clef (moy. partages)   
25. kw_min_avg : Moy. mot‐clef (min. partages)   
26. kw_max_avg : Moy. mot‐clef (max. partages)   
27. kw_avg : Moy. mot‐clef (moy. partages)   
28. self_reference_min_partages : Min. partages des articles liés sur le site  
29. self_reference_max_partages : Max. partages des articles liés sur le site  
30. self_reference_moy. de_partagess : Moy. partages des articles liés sur le site  
31. weekday_is_monday : L’article a‐t‐il été publié un lundi?   
32. weekday_is_tuesday : L’article a‐t‐il été publié un mardi?   
33. weekday_is_wednesday : L’article a‐t‐il été publié un mercredi?   
34. weekday_is_thursday : L’article a‐t‐il été publié un jeudi?   
35. weekday_is_friday : L’article a‐t‐il été publié un vendredi?   
36. weekday_is_saturday : L’article a‐t‐il été publié un samedi?   
37. weekday_is_sunday : L’article a‐t‐il été publié un dimanche?   
38. is_weekend : L’article a‐t‐il été publié durant le weekend?   
39. LDA_00 : Proximité au thème 0   
40. LDA_01 : Proximité au thème 1   
41. LDA_02 : Proximité au thème 2   
42. LDA_03 : Proximité au thème 3   43. 
LDA_04 : Proximité au thème 4   
44. global_subjectivity : Subjectivité du texte  
45. global_sentiment_polarité : Polarité du sentiment de l’article  
46. global_rate_positive_mots : Taux de mots positifs de l’article   
47. global_rate_negative_mots : Taux de mots négatifs de l’article   
48. rate_positive_mots : Taux de mots positifs parmi les non‐neutres   
49. rate_negative_mots : Taux de mots négatifs parmi les non‐neutres  
50. moy. de_positive_polarité : Polarité  moy. des mots positifs  
51. min_positive_polarité : Polarité  min. polarité des mots positifs   
52. max_positive_polarité : Polarité  max. polarité des mots positifs   
53. moy. de_negative_polarité : Polarité  moy. polarité des mots négatifs   
54. min_negative_polarité : Polarité  min. polarité des mots négatifs  
55. max_negative_polarité : Polarité  max. polarité des mots négatifs  
56. Titre_subjectivity : Subjectivité du titre   
57. Titre_sentiment_polarité : Polarité du titre   
58. abs_Titre_subjectivity : Niveau absolu de subjectivité  
59. abs_Titre_sentiment_polarité : Niveau absolu de polarité  
60. shares : Nombre de partages (variable cible) 
