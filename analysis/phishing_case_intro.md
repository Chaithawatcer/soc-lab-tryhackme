# Phishing Case 1 – Introduction to Phishing
<img width="1908" height="928" alt="image" src="https://github.com/user-attachments/assets/646459f1-64d0-433c-af61-944a2caed5ff" />

## 8814 – Inbound Email Containing Suspicious External Link
<img width="1453" height="563" alt="image" src="https://github.com/user-attachments/assets/470d6c0f-aaf9-45e8-984c-5bfa7afffc5d" />

## Add action
<img width="1550" height="123" alt="image" src="https://github.com/user-attachments/assets/c0ac9b3c-bea9-4e7e-8d30-4617700ecd62" />

## Analyst event
- Analyst suspicious external link.

## Open Analyst VM
- Search hrconnex.thm for check URL.
<img width="1919" height="929" alt="image" src="https://github.com/user-attachments/assets/cecf7b82-a170-49fc-8d28-3dcd45511ef6" />


- Status is CLEAN
<img width="850" height="862" alt="image" src="https://github.com/user-attachments/assets/97a646e8-f5bd-4417-b450-283fa1ba295e" />

- This seems to contradict our earlier suspicions. The email actually seems to be from a third-party HR partner. I guess it is a false positive. Write the incident report and classify as false positive.

## Write case report
- Write case report as false positive and and more description.
<img width="916" height="400" alt="image" src="https://github.com/user-attachments/assets/41c2d33a-eef9-42c2-91a4-daf31d4ea239" />

## 8815 – Inbound Email Containing Suspicious External Link
<img width="1533" height="455" alt="image" src="https://github.com/user-attachments/assets/286a27fb-833c-48dd-a4a9-c62fad1d2d49" />

## Add action
<img width="1557" height="120" alt="image" src="https://github.com/user-attachments/assets/a328b7b2-9408-444c-b57a-5c272ba82bd3" />

## Analyst event
- Analyst suspicious sender and URL.
<img width="721" height="863" alt="image" src="https://github.com/user-attachments/assets/95fc1794-4391-41a5-8347-9a4abb759319" />
<img width="715" height="865" alt="image" src="https://github.com/user-attachments/assets/ce5c047a-6c2a-4ee8-81c3-55c96126122f" />
- Email sender status is clean but url is malicious.
- Analyst SIEM log.
<img width="1514" height="832" alt="image" src="https://github.com/user-attachments/assets/25198709-cfb0-4e19-99f9-145bd4d8313b" />
- user try to access the url but firewall blooked.

## Write case report
<img width="1004" height="698" alt="image" src="https://github.com/user-attachments/assets/6e432d38-e8ee-452d-84e0-0382f09504eb" />


## 8816 - Access to Blacklisted External URL Blocked by Firewall
<img width="1527" height="796" alt="image" src="https://github.com/user-attachments/assets/5a39f133-451d-4c32-af5f-8093ae4e8d60" />

## Add action
<img width="1550" height="128" alt="image" src="https://github.com/user-attachments/assets/e7f79bf1-25d9-4109-b217-9ed21587cbca" />

## Analyst event
- Analyst suspicious ip and link URL.
- Search 67.199.248.11 for check suspicious IP and URL http://bit.ly/3sHkX3da12340.
- IP and URL Report status is MALICIOUS.
<img width="850" height="876" alt="image" src="https://github.com/user-attachments/assets/49bef38c-63a2-430c-bca7-1d30448c9841" />
<img width="848" height="842" alt="image" src="https://github.com/user-attachments/assets/4de57020-c0f1-420f-863e-8d13a2614d8b" />

## Write case report
<img width="947" height="568" alt="image" src="https://github.com/user-attachments/assets/c7be3294-3913-461e-908c-ef5e2befb86d" />

