# Generation mask for data

Data generation that was changed:
1. Table warehouse
	* w_name = name-<random string(5)>
	* w_street_1 = street1-<random string(10)>
	* w_street_2 = street2-<random string(10)>
	* w_city = city-<random string(10)>
	* w_zip = zip-<random number(5)>
2. Table district
	* d_name = name-<random string(5)>
	* d_street_1 = street1-<random string(10)>
	* d_street_2 = street2-<random string(10)>
	* d_city = city-<random string(10)>
	* d_zip = zip-<random number(5)>
3. Table customer
	* c_first = first-<random string(2,10)>
	* c_street_1 = street1-<random string(10)>
	* c_street_2 = street2-<random string(10)>
	* c_city = city-<random string(10)>
	* c_zip = zip-<random number(5)>
	* c_data = <1 random char string(300,500)>
4. Table history
	* h_data = <1 random char string(12,24)>
5. Table item
	* i_name = item-<i_im_id>-<i_price>-<random string(5)>
	* i_data = data-<i_name>-<random string(8)>
6. Table stock
	* s_dist_01 = <1 random char string(24)>
	* s_dist_02 = <1 random char string(24)>
	* s_dist_03 = <1 random char string(24)>
	* s_dist_04 = <1 random char string(24)>
	* s_dist_05 = <1 random char string(24)>
	* s_dist_06 = <1 random char string(24)>
	* s_dist_07 = <1 random char string(24)>
	* s_dist_08 = <1 random char string(24)>
	* s_dist_09 = <1 random char string(24)>
	* s_dist_10 = <1 random char string(24)>
	* s_data = <1 random char string(26,50)>
7. Table order_line
	* ol_dist_info = <1 random char string(24)>
