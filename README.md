## PyTLE

PyTLE is a set of utilities for parsing and processing NORAD two-line element sets, and returning the output as JSON.
Currently supports simple parsing of TLE parameters.  

### Sample Output

    {
        "arg_of_perigee": 220.8582, 
        "bstar": 2.1971, 
        "classification": "U", 
        "eccentricity": 0.0011688, 
        "element_number": 584, 
        "epoch_day": 17.908749, 
        "epoch_year": 2013, 
        "inclination": 101.4201, 
        "international_designator": "74089B", 
        "line1_checksum": true, 
        "line2_checksum": true, 
        "mean_anomaly": 171.2803, 
        "mean_motion": 12.53593914, 
        "mean_motion_ddot": 0.0, 
        "mean_motion_dot": -1.6e-07, 
        "name": "AO-07", 
        "ra_of_asc_node": 12.9443, 
        "rev_at_epoch": 74695, 
        "satellite_number": 7530
    }

