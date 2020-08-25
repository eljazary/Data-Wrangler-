# 1-Assessment summary 
## 1.1-	Twitter_archive_enhanced .csv read as df_tw 
##### •	`Twitter_id` should be a string value not a int  and don’t duplicated as this column is  a unique value 
##### •	`Time stamp` have incorrect  type string and should be  
##### •	`Doggo`  , `floofer` , `puupper` , `puppo` should be in column which represent the dog age stage (tidy issue ) 
##### • `url_expanded` have missing value .
##### • suggessting to substitue `rating_numerator`, `rating_denominator`  with column called `rating`

## 1.2-	df_image_pred 
##### •	 Tweet_id  also should be a string and unique value 
##### •	 i suggest that `P1_conf , p2_conf , p3_conf  ` substituted by p max which represent highest value of p and take theequivalent value from P  column (
##### •	`P1_dog  , p2_dog , p3`_dog should be one column and if all hav and pe false value  rows , this rows should be deleted (tidy and quality )
##### •	Check `jpg_ul` for duplication and remove this duplication in cleaning 

## 1.3-	Twitter_df 
##### •	Some empty column should be removed like ( `contributors` , `coordinates` )
##### •	 Column ( `in_reply_to_screen_name `, `n_reply_to_status_id `,  `in_reply_to_status_id_str` , `in_reply_to_user_id`,`in_reply_to_user_id_str `)       


