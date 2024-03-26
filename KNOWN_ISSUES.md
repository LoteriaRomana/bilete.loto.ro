* ~~Cel mai probabil emailurile vor ajunge în folderul Spam. Se va implementa DKIM/DMARC/BIMI/SNDS și [ce-o mai cere Google](https://support.google.com/a/answer/81126) începând din martie 2024.~~ Implementat DKIM/DMARC, ar trebui sa nu mai intre in Spam.
* ~~Unele emailuri pot ajunge cu întârziere de aproximativ 10 minute - cauza fiind eșuarea unor interogări DNS la prima încercare. Investigăm.~~ Remediat.
* Yahoo refuza majoritatea mesajelor. Ne-am inregistrat in CFL la https://senders.yahooinc.com si asteptam.
