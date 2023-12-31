﻿
# tiktouk_kaneki NextJs 13 / (tiktouk_kaneki-nextjs)

### Learn how to build this!

If you'd like a step-by-step guide on how to build this just **CLICK THE IMAGE BELOW**

![image](https://github.com/IlyassEzzam/tiktouk_kaneki/assets/110631781/dd36622b-d63c-43fa-bdb9-13d4311dede6)




## AppWrite Schema

### Database Name: tiktok-clone

### Profile Collection:
| Key | Type |
| --- | --- |
| `Document ID` | String |
| `image` | String |
| `bio` | String |
| `user_id` | String |
| `name` | String |

Profile Indexes:
| KEY           | TYPE          | ATTRIBUTE     | ASC/DESC      |
| ------------- | ------------- | ------------- | ------------- |
| user_id       | key           | user_id       | asc           |
| name          | fulltext      | name          | asc           |

Profile Settings (Update Permissions):
| Add Role      | PERMISSIONS   |
| ------------- | ------------- |
| All guests    | Read          |
| All users     | Create, Read, Update, Delete |

### Post Collection:
| Key | Type |
| --- | --- |
| `Document ID` | String |
| `user_id` | String |
| `video_url` | String |
| `text` | String |
| `created_at` | String |
    
Post Indexes:
| KEY           | TYPE          | ATTRIBUTE     | ASC/DESC      |
| ------------- | ------------- | ------------- | ------------- |
| user_id       | key           | user_id       | asc           |

Profile Settings (Update Permissions):
| Add Role      | PERMISSIONS   |
| ------------- | ------------- |
| All guests    | Read          |
| All users     | Create, Read, Update, Delete |

### Like Collection:
| Key | Type |
| --- | --- |
| `Document ID` | String |
| `user_id` | String |
| `post_id` | String |

Like Indexes: 
| KEY           | TYPE          | ATTRIBUTE     | ASC/DESC      |
| ------------- | ------------- | ------------- | ------------- |
| user_id       | key           | user_id       | asc           |
| id            | unique        | id            | asc           |
| post_id       | key           | post_id       | asc           |

Like Settings (Update Permissions):
| Add Role      | PERMISSIONS   |
| ------------- | ------------- |
| All guests    | Read          |
| All users     | Create, Read, Update, Delete |

### Comment Collection:
| Key | Type |
| --- | --- |
| `Document ID` | String |
| `user_id` | String |
| `post_id` | String |
| `text` | String |
| `created_at` | String |
    
Comment Indexes:
| KEY           | TYPE          | ATTRIBUTE     | ASC/DESC      |
| ------------- | ------------- | ------------- | ------------- |
| post_id       | key           | post_id       | asc           |

Comment Settings (Update Permissions):
| Add Role      | PERMISSIONS   |
| ------------- | ------------- |
| All guests    | Read          |
| All users     | Create, Read, Update, Delete |

![image](https://github.com/IlyassEzzam/tiktouk_kaneki/assets/110631781/7c280bf3-2f9e-446c-93c0-ed1c6bdaca2f)
![image](https://github.com/IlyassEzzam/tiktouk_kaneki/assets/110631781/9b7ef15a-8c1b-4504-b262-72252fb90227)
![image](https://github.com/IlyassEzzam/tiktouk_kaneki/assets/110631781/c0d35280-1628-4287-ab2e-5f86ece7c8ea)
![image](https://github.com/IlyassEzzam/tiktouk_kaneki/assets/110631781/ea37a67c-b30a-4ba5-8df9-96e9a10bc87f)
![image](https://github.com/IlyassEzzam/tiktouk_kaneki/assets/110631781/6a31b120-0f50-4b33-a631-40bf206aa921)
![image](https://github.com/IlyassEzzam/tiktouk_kaneki/assets/110631781/5f1efdf9-1f86-4fb5-8555-bbc5ca70b913)
![image](https://github.com/IlyassEzzam/tiktouk_kaneki/assets/110631781/d65af8c8-e86e-4e61-948f-8be9a35e9345)



