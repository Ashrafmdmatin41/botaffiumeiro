## WARNING: BREAKING CHANGES
The way to configure Amazon links has changed.
This is because it has been unified with affiliate stores and now allows handling Amazon from different countries.
The new way to configure it is as follows:

amazon:
  amazon.es: botaffiumeiro_cofee-21
  amazon.com: hectorzindomo-20
  amazon.com.au: hectorzindomo-22
  amazon.co.uk: hectorzindomo-21
  amazon.fr: hectorzindo0d-21
  amazon.it: hectorzindo04-21
  amazon.de: hectorzindo0e-21

## New features
- allow use of HTML in predefined messages: We can now use bold, italic, etc styles in the predefined messages as shown in the following image:
![image](https://github.com/user-attachments/assets/39fb1059-5e34-4c1e-b988-1ba6aebb51f8)
- You can use custom commands so that your Telegram group users can request AliExpress discount codes: /discount /aliexpress, etc.
- Improved Logging levels
- We've replaced the classic "give a coffee" with a parameter that represents the approximate % (as it is random) of times the affiliate link will belong to the creators. This parameter is entirely optional and can be set between 0 and 100%; by default, it is set to 10%. Thanks!

