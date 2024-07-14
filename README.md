
    """
    return EXPECTED_BAKE_TIME - elapsed_bake_time

    
    


def preparation_time_in_minutes(number_of_layers):
    
    """Calculate preparation time in minutes.

     :param number_of_layers: int - number of layers.
     :return: int - two times(time each layer take to prepare) the number of layers.

     Function takes number of layers needed for lasagna recipe as an 
     argument and returns how much time it takes to prepare lasagna before cooking.
    """
    return 2 * number_of_layers

def elapsed_time_in_minutes(number_of_layers, elapsed_bake_time):

    """Calculate the elapsed time for preparing and cooking lasagna.

    :param number_of_layers: int - the number of layers in lasagna.
    :param elapsed_bake_time: int - elapsed bake time.
    :return: int - total time elapsed (in minutes) preparing and cooking.

    function takes two integers number of lasagna layers and the
    time already spent cooking as arguments and calculates the total elapsed 
    minutes spent preparing and cooking the lasagna.
    """
    preparation_time = preparation_time_in_minutes(number_of_layers)
    return preparation_time+ elapsed_bake_time
        
    
