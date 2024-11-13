##### AD GPO sur le clients:
##### clic sur "View" =>

![VM 1](https://github.com/user-attachments/assets/d37402f9-e588-4d37-abfe-8f7820416ac4)
##### Changer "quick access" en This PC et décocher les deux options en bas
![VM 1](https://github.com/user-attachments/assets/f6eebabf-6f98-4d6b-8d75-7e49d90e875d)
##### Résultat attendu
![VM 1](https://github.com/user-attachments/assets/3d302cd2-d1d3-4156-aea2-522243acafe6)
##### :arrow_up: Clic droit dans le blanc, en bas à côté de Local Disk(C:) => "Properties"
##### Puis clic sur "Advanced system settings"(bleu) => renseigner login et password de l'AD => "Change..."(rouge)
![VM 1](https://github.com/user-attachments/assets/1999e37d-e398-498e-b2df-2a727b7ef75a)
##### Choisir la partie "Domain" et renseigner le domaine créer dans l'AD.
![VM 1](https://github.com/user-attachments/assets/14627ca2-8e8b-4642-bd23-7cc1b99e65ce)
##### Le pc client va reboot, et depuis l'AD on aura la main sur toutes les configuration de ce PC depuis GPO de l'AD.

## Pour y appliquer les régles :
##### Se rendre sur cette page : 
![vm 1](https://github.com/user-attachments/assets/bef961d1-2071-4962-8134-48523ada8f20)
##### :arrow_up: => Group Policy Management.
##### Sur la page Group Policy Management : 
![vm 1](https://github.com/user-attachments/assets/7bc1754a-5761-4ce7-aa4f-3f227f49edf6)
##### Dérouler Forest => Domains => domain.local => Domain controllers Policy => clic droit => Default Domain Controllers Policy => Edit
![vm 1](https://github.com/user-attachments/assets/29d472fa-6fa3-4007-94fb-395c71a7a008)
##### Dans cette fenêtre toutes les régle User et Computer son réalisable :
![vm 1](https://github.com/user-attachments/assets/59942eaa-1e84-44f2-b43e-656c6b4e5c71)













