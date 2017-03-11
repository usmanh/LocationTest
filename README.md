# LocationTest

This Sample Project gets the current Country of the user from network carrior and compares it with all the available
country codes to obtain the exact country code based on which the background image is set.
Currently showing images for three countries for UAE, United States and Great Britian. More images could be added as per 
requirments, for this example these images serve the purpose. 

This sample is made as per the requirments i.e. Getting the country information from the network provider, but in some cases 
a user might not have the Network of other countries immidiately on landing. For this secenario the current time zone could be
used. 

#Notice
Not using the NSlocale because for a person travling from one country to another the Locale is set to the base country. 
