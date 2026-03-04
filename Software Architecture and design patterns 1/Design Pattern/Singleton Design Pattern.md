==Application එක තුළ 
class එකක instance එකක් (object එකක්) පමණක් create වීමට allow කිරීම 
සහ එය global access point එකක් ලෙස ලබා දීම.==
**Singleton Design Pattern** කියන්නේ _Creational Design Pattern_ එකක්.

- `private constructor`    
- `static instance variable`
- `public static getInstance()` method

#### Why we use it ?
- **Memory efficiency** – unnecessary objects create වීම වැළැක්වීම.
- **Centralized control** – shared resource එකක් control කිරීම.
- **Global access** – project එකේ ඕනෑම class එකකින් එකම instance එක access කිරීම.

#### Example Scenarios:
- Database Connection 
	(Hibernate `SessionFactory`)		
- Logger
- Configuration Manager
- Cache Manager

