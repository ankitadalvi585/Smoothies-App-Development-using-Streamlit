The project involves the development of a web-page designed using StreamLit for ordering customized smoothies. Users select their desired fruits from a variety of options available on the web-page. Nutritional information for each fruit is retrieved from the FruityVice API to assist users in making informed choices.

Upon placing an order, the selected smoothie specifications are stored in a database (Snowflake) for tracking and processing. The order is initially listed in the "Pending Smoothie Orders" queue within an employee application, indicating that it requires preparation.

Once the order is fulfilled by employees, its status is updated in the database to reflect completion. Subsequently, the entry is removed from the "Pending Smoothie Orders" queue, ensuring accurate management of order statuses and workflow.

Customized Smoothie Orders page:
![image](https://github.com/ankitadalvi585/melanies_smoothies/assets/115281341/a90c0670-be54-4dbe-a4f9-82f5058b880e)
![image](https://github.com/ankitadalvi585/melanies_smoothies/assets/115281341/7f157abe-4e98-4c1d-8a3e-99782342e9ac)
![image](https://github.com/ankitadalvi585/melanies_smoothies/assets/115281341/1e660cb4-fa1a-4ba3-a6cd-6beef1e6fb3e)

Pending Smoothie Orders page:

![image](https://github.com/ankitadalvi585/melanies_smoothies/assets/115281341/5dcf3ac7-aec0-4a9a-845f-1e697e5c4102)
