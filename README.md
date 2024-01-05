# Ware-Flow

## Overview
Ware Flow is a Full-Stack web app with role-based access for managing and tracking warehouse operations. This full stack web app is written in Vue.js for the front end, while using Java Springboot to handle CRUD operations with a MySQL database hosted on AWS RDS. 
![image](https://github.com/xchkcode0803/Ware-Flow/assets/109048196/cffffdea-9ccd-4104-8e29-861938ff81d8)
## Functionalities 
This software provides the following functionalities: 
- Role-based access to different content. Different roles with different authorizations can view/modify different content in the web app.
- Record keeping of all the transactions happening across all of the warehouses.
- Security: This system uses JWT token for sign-in authorizations. 
- Item management: Manager has the ability to categorize and assign goods to different warehouses. Manager can also look up certain goods using keyword search.
- User management: Super manager has the ability to add/drop accounts having access to the warehouse management system and edit each account's authorization level.
- Highly customizable: With some small tweaks to the front-end, this warehouse management system can be easily changed to many other management systems! 

### Role-based access 
There are three levels of authorization to this management system: 
- Super Manager: super manager can add/drop normal managers to the system + get access to all of the users, categories, goods, and warehouses present on the system.There is only 1 super manager allowed per system.
![image](https://github.com/xchkcode0803/Ware-Flow/assets/109048196/cffffdea-9ccd-4104-8e29-861938ff81d8)

- Normal manager: normal managers has access to all of the users, categories, goods, and warehouses present on the system. Normal managers can also add/drop normal users to the system.
![image](https://github.com/xchkcode0803/Ware-Flow/assets/109048196/4fe8b2fb-16c7-46eb-905a-2ff3969b4d27)


- Normal user: normal users can view/edit all of the items on the system and they can also get an overview of the transaction records happening within the system. 
![image](https://github.com/xchkcode0803/Ware-Flow/assets/109048196/feec9e68-2df6-41cf-b3d7-d6f334477684)


















