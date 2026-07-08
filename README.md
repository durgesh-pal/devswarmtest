# devswarmtest
def process_data():
    # TEST BUG 1: Hardcoded sensitive secret key
    api_key = "AIzaSyFakeKey12345Secret" 
    
    # TEST BUG 2: Terrible performance nested loops
    for i in range(100):
        for j in range(100):
            for k in range(100):
                print("Processing slowly...") 
