<p align="right">
<a href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fgithub.com%2Fcabani%2FForcastingParcels&t=MForcastingParcels&quote="><img src="http://acabani.free.fr/github/Facebook.png" alt="facebook " /></a> 
<a href="https://twitter.com/intent/tweet?text=ForcastingParcels%20https%3A%2F%2Fgithub.com%2Fcabani%2FForcastingParcels&related=AddToAny,micropat"><img src="http://acabani.free.fr/github/Twitter.png" alt="tweeter" /></a>
<a href="https://www.linkedin.com/sharing/share-offsite/?url=https%3A%2F%2Fgithub.com%2Fcabani%2FForcastingParcels"><img src="http://acabani.free.fr/github/Linkedin.png" alt="linkedin" /></a>
</p>

# Prediction of the Load of a Parcel Pick-Up Point: Data-Driven vs Model-Driven approaches

Along with home delivery, Pick-Up Points (PUP) have been developed as an alternative delivery option for online purchases to offer more extensive hour ranges for picking up parcels and reducing transportation fees. A parcel purchased online is delivered to a PUP point and waits until being picked up by the customer or returned to the original warehouse if its sojourn time is over. When the chosen PUP is overloaded, the parcel may be refused and delivered to the next available PUP on the carrier tour.

This paper presents and compares forecasting approaches for the load of a PUP to help PUP managing companies balance delivery flows and reduce PUP overload. The parcel life-cycle has been taken into account in the forecasting process, via models of the flow of parcel orders, of the parcel delivery delays, and of the pick-up process. Model-driven and data-driven approaches are compared in terms of load-prediction accuracy. 

For more details about this work:
>  Thi Thu Tam Nguyen, Adnane Cabani, Iyadh Cabani, Koen De Turck, and Michel Kieffer, "Prediction of the Load of a Parcel Pick-Up Point: Data-Driven vs Model-Driven approaches", (Under Review).

# Dataset
The dataset presented in this github ([data.csv](https://github.com/cabani/ForcastingParcels/blob/main/data.csv)) is collected from one Pick-Up Point. Each line of the csv file contains for each parcel: 
- Id_parcel: the ID of the parcel
- DateR: the date when the parcel is ready for expedition
- DateE: the date when the parcel is taken over by a carrier
- DateD: the delivery date
- DateP: the pick up date
- Carrier: the carrier 
