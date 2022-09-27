# local_json_data_read
The process of reading from the local JSON file in the application, which is generally used in applications that do not need internet, without making any service calls.
In order to extract data from a data source in the current application, I created a new folder with the name raw under the res folder and created the data source “***.json” that I used in the raw folder.
Modeling POJOs must be written in order for the data to be read and used within the application. You can use http://www.jsonschema2pojo.org/ to quickly create models.

I created a folder called model in the project so that all of the classes created with the preview button can be found together.

I copied the created POJO and put it in the model folder.
