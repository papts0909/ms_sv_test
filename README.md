return (new Response(
            json_encode(array(
                'STATUS' => 'AUTHENTICATED' , 
                'data'=> ['a' => 1, 'b' => 2])
            ), 404))
        ->header('Content-Type', 'application/json');
