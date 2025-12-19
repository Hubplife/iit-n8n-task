In This I tried to build a simple AI processing pipeline that combines external data retrieval with large language model reasoning. I did it with dividing them into groq and juni.ai configurations.
I did not managed to do this exercise acording to the task, because in groq configuration the JSON code was not working and it was constantly printing the errors telling that some parameters are unsupported. The same errors happened when I tried to use this parameters with the option "fields below". I changed the code in the second http request and added edit field to filter the data. And it worked.

Creating a new workflow

![10_5](l10_5.png)

Configuring Jina.ai HTTP Request

![l10_6](l10_6.png)

Added editing field

![l10_9](l10_9.png)

Configuring Groq http request configuration

![l10_7](l10_7.png)



Testing the workflow

![l10_8](l10_8.png)