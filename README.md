# otaapi

API documentation 

Get All Manga 

https://creatordesk.otamyanmar.com/manga/read.php

Sample Respond : 

{"records":[{"manga_id":"23","chpt_count":"0","manga_title":"Death is the only ending for the villainess","manga_cover":"https:\/\/creatordesk.otamyanmar.com\/\/static\/manga\/121097566_200856061486909_6385252596751674747_n.jpg","manga_disp":"\u101e\u1030\u1019\u1018\u101d\u101c\u103d\u1010\u103a\u101c\u1015\u103a\u1019\u1030\u1000\u102d\u102f\u1014\u1031\u102c\u1000\u103a\u1006\u102f\u1036\u1038\u1010\u1031\u102c\u1037\u101b\u1001\u1032\u1037\u1015\u1031\u1019\u1032\u1037\u101c\u1032\r\n\u101d\u1019\u103a\u1038\u101e\u102c\u101c\u102d\u102f\u1037\u1019\u1006\u102f\u1036\u1038\u1001\u1004\u103a\u1019\u103e\u102c\u1018\u1032\r\n\u1001\u103d\u1031\u1038\u101b\u1030\u1038\u1010\u1005\u103a\u1000\u1031\u102c\u1004\u103a\u101c\u102d\u102f\u1037\u101e\u1010\u103a\u1019\u103e\u1010\u103a\u1001\u1036\u1011\u102c\u1038\u101b\u1010\u1032\u1037\u1021\u1019\u103c\u103e\u1031\u102c\u1000\u103a\u1005\u102c\u1017\u102e\u101c\u1014\u103a\u1014\u1031\u101b\u102c\u1000\u102d\u102f\u101b\u1031\u102c\u1000\u103a\u1001\u1032\u1037\u1015\u103c\u102e\u1038\u1021\u101e\u1000\u103a\u101b\u103e\u1004\u103a\u1016\u102d\u102f\u1037\u1000\u103c\u102d\u102f\u1038\u1005\u102c\u1038\u1010\u1032\u1037\u1021\u1001\u102b","manga_like_count":"0","created":"2021-08-10 05:19:38","category_id":"1","category_name":"Isekai"}, ] }

Search Manga 

https://creatordesk.otamyanmar.com/manga/search.php?s= 'keywprd'

Sample Respond : 

{"records":[{"manga_id":"23","chpt_count":"0","manga_title":"Death is the only ending for the villainess","manga_cover":"https:\/\/creatordesk.otamyanmar.com\/\/static\/manga\/121097566_200856061486909_6385252596751674747_n.jpg","manga_disp":"\u101e\u1030\u1019\u1018\u101d\u101c\u103d\u1010\u103a\u101c\u1015\u103a\u1019\u1030\u1000\u102d\u102f\u1014\u1031\u102c\u1000\u103a\u1006\u102f\u1036\u1038\u1010\u1031\u102c\u1037\u101b\u1001\u1032\u1037\u1015\u1031\u1019\u1032\u1037\u101c\u1032\r\n\u101d\u1019\u103a\u1038\u101e\u102c\u101c\u102d\u102f\u1037\u1019\u1006\u102f\u1036\u1038\u1001\u1004\u103a\u1019\u103e\u102c\u1018\u1032\r\n\u1001\u103d\u1031\u1038\u101b\u1030\u1038\u1010\u1005\u103a\u1000\u1031\u102c\u1004\u103a\u101c\u102d\u102f\u1037\u101e\u1010\u103a\u1019\u103e\u1010\u103a\u1001\u1036\u1011\u102c\u1038\u101b\u1010\u1032\u1037\u1021\u1019\u103c\u103e\u1031\u102c\u1000\u103a\u1005\u102c\u1017\u102e\u101c\u1014\u103a\u1014\u1031\u101b\u102c\u1000\u102d\u102f\u101b\u1031\u102c\u1000\u103a\u1001\u1032\u1037\u1015\u103c\u102e\u1038\u1021\u101e\u1000\u103a\u101b\u103e\u1004\u103a\u1016\u102d\u102f\u1037\u1000\u103c\u102d\u102f\u1038\u1005\u102c\u1038\u1010\u1032\u1037\u1021\u1001\u102b","manga_like_count":"0","created":"2021-08-10 05:19:38","category_id":"1","category_name":"Isekai"}, ] }


Get Manga info 

https://creatordesk.otamyanmar.com/manga/read_one.php?manga_id= 'manga id'

Sample Respond 

{"manga_id":"21","chpt_count":"0","manga_title":"The Ranker Who Live Twice","manga_cover":"https:\/\/creatordesk.otamyanmar.com\/\/static\/manga\/103110343_168197688086080_8697050634944896927_n.jpg","manga_disp":"His brother had been the victim of deceit in this universe as he climbed up the wall.\r\n\r\nAfter learning the facts, Yeon-woo and his brother's diary decided to climb up the tower.\r\n\r\nYeon-woo then goes through the same trials and battles that his younger brother did as an anonymous player.","manga_like_count":"0","created":null,"category_id":"1","category_name":"Isekai"}

Get Manga Chapters

https://creatordesk.otamyanmar.com/manga/read_Chpt.php?manga_id= 'id'

Sample Respond 

{"chpts":[{"manga_id":"21","chpt_id":"319","chpt_thumb":"https:\/\/cdn.otamyanmar.com\/thumb\/manga2021080974539.jpg","chpt_sum":"Chapter 87","chpt_num":"87"},{"manga_id":"21","chpt_id":"292","chpt_thumb":"https:\/\/cdn.otamyanmar.com\/thumb\/manga202108052487.jpg","chpt_sum":"Chapter 86","chpt_num":"86"},]}


Get Chapter Contents 
https://creatordesk.otamyanmar.com/manga/read_mgcontent.php?chpt_id= 'id'

Sample Respond

{"cont":[{"c_id":"12602","chpt_id":"319","url":"https:\/\/cdn.otamyanmar.com\/content\/mgpan2021080921488.jpg","c_num":"0"},{"c_id":"12603","chpt_id":"319","url":"https:\/\/cdn.otamyanmar.com\/content\/mgpan2021080974277.jpg","c_num":"1"},]}


