IUG  
Web Programming 2 - SICT 2308  
ِِAssginment 1

id: 120171952

<?php
        $Course = array("web2" => 85 , "DataBase" => 80 , "computerArt" => 77 , "Prog3" =>  98);
        foreach( $Course as $key => $value ){
        echo $key."=>".$value." ";
		}
