![](/img/Ventilators_feat.jpg)

# Covent19
This repository is a collection of information about the global Open Innovation Effort to Design a Rapidly Deployable Mechanical Ventilator, and an attempt at solidifying a practical design for low resource countries.

# Motivation
I summarised motivations for this project on this post:
https://medium.com/@alitarraf/makers-against-covid19-with-diy-ventilators-cece301787f0?sk=f5902e88e8bedd746325b3d50259d661


# Ventilator Requirements
[Work In Progress]  

The main requirement of any mechanical ventilator is to oxygenate lungs in a certain specific pressure and volume depending on operation. This plot from the [European Journal of Anaesthesiology](https://journals.lww.com/ejanaesthesiology/fulltext/2008/02000/optimal_ventilator_settings_in_acute_lung_injury.1.aspx) reveals the adequate operation range.
![](/img/PV.png)

## Specifications

Unclassified features:
- Control O2 flow
- Control Pressure of the respiratory system
- Control humidity of gas delivered into the respiratory system

Minimum must have features:

Extra features:

Wish for features:

Sample specifications taken from [Frontiers Technology of the UK Department of International Development](https://medium.com/frontier-technology-livestreaming/frontier-tech-4-covid-action-emerging-market-ventilation-systems-9c818cb46189) and from the UK Government [Rapidly Manufactured Ventilator System Specification](https://www.gov.uk/government/publications/coronavirus-covid-19-ventilator-supply-specification/rapidly-manufactured-ventilator-system-specification) :

1. Be reliable. It must work continuously without failure (100% duty cycle) for blocks of 14days — 24 hours a day. If necessary, the machine may be replaced after each block of 14 days x 24 hours a day use.
2. Provide at least two settings for volume of air/air O2 mix delivered per cycle/breath. These settings to be 450ml +/- 10ml per breath and 350ml +/- 10ml per breath.
3. Provide this air/air O2 mix at a peak pressure of 350 mm H2O.
4. Have the capability for patient supply pipework to remain pressurised at all times to 150mm H20.
5. Have an adjustable rate of between 12 and 20 cycles/breaths per minute.
6. Deliver at least 400ml of air/air 02 mix in no more than 1.5 seconds. The ability to change the rate at which air is pushed into the patient is desirable but not essential.
7. Be built from O2 safe components to avoid the risk of fire and demonstrate avoidance of hot spots.
Be capable of breathing for an unconscious patient who is unable to breathe for his or herself. Ability to sense when a patient is breathing, and support that breathing is desirable but not essential.
8. Be able to supply pure air and air O2 mix at a range of concentrations including at least 50% and 100% Oxygen. Oxygen shortages are not expected, but the ability to attach a Commercial Off The Shelf (COTS) portable O2 concentrator machine may be a useful feature.
9. Support connections for hospital Oxygen supplies — whether driven by piped or cylinder infrastructure
10. Be compatible with standard COTS catheter mount fittings (15mm Male 22mm Female)
11. Fail SAFE, ideally generating a clear alarm on failure. Failure modes to be alarmed include (but are not limited to) pressure loss and O2 loss

# Design Alternatives
[Work In Progress]

- Automated Ambu Bag
- Automated Mapleson Circuit
- Upgrading a CPAP machine

# Tests & Validation
TBD

# Legal concerns
[Work In Progress]

- [US FDA regulations summarised by this reddit post along with failure modes](https://www.reddit.com/r/engineering/comments/fl9brm/a_primer_on_fda_regulations_usa_because/?utm_medium=android_app&utm_source=share)

# Additional Resources

## Challenges
- [Covent Challenge by Massassuchets General Hospital](https://www.coventchallenge.com/)
- [Frontiers Technology of the UK Department of International Development](https://medium.com/frontier-technology-livestreaming/frontier-tech-4-covid-action-emerging-market-ventilation-systems-9c818cb46189)
- [RFP for a Rapidly Manufactured Ventilator System by the UK government](https://www.gov.uk/government/publications/coronavirus-covid-19-ventilator-supply-specification/rapidly-manufactured-ventilator-system-specification)
- [Opensource ventilators register your interest](https://opensourceventilator.ie/)

## Community & Discussion & Research
- [Compilation of research folders from the Project OpenAir](https://drive.google.com/drive/folders/1qtQlHXeLzfgIWJPnlad803tzfmr0Z_7_)
- [Specifications for simple open source mechanical ventilator Julian Botta, Johns Hopkins Emergency Medicine Resident PGY-3
Twitter: @julianbotta](https://docs.google.com/document/d/1FNPwrQjB1qW1330s5-S_-VB0vDHajMWKieJRjINCNeE/preview?fbclid=IwAR3ugu1SGMsacwKi6ycAKJFOMduInSO4WVM8rgmC4CgMJY6cKaGBNR14mpM)
- Facebook Group [Open Source Covid19](https://www.facebook.com/groups/670932227050506)
- Article by Vice: [People Are Trying to Make DIY Ventilators to Meet Coronavirus Demand](https://www.vice.com/en_us/article/5dm4mb/people-are-trying-to-make-diy-ventilators-to-meet-coronavirus-demand)
- [Research compiled related to Open Source Ventilator Designs](docs.google.com/document/d/1RDihfZIOEYs60kPEIVDe7gmsxdYgUosF9sr45mgFxY8/mobilebasic#)
- [ULTIMATE MEDICAL HACKATHON: HOW FAST CAN WE DESIGN AND DEPLOY AN OPEN SOURCE VENTILATOR?](https://hackaday.com/2020/03/12/ultimate-medical-hackathon-how-fast-can-we-design-and-deploy-an-open-source-ventilator/)
- [Hackaday Reddit discussion](https://www.reddit.com/r/Coronavirus/comments/fkhgu3/12_million_member_we_can_do_this_guys_open_source/?utm_medium=android_app&utm_source=share)
- [Discussion around prototype Arduino Ambu Bag](https://www.reddit.com/r/arduino/comments/fkhyp5/using_arduino_to_combat_the_covid19_ventilator/?utm_medium=android_app&utm_source=share) - a lot of interesting comments and insights
- [3D Printing of a respirator valve in Italy](https://hackaday.com/2020/03/16/3d-printed-parts-keep-respirators-operational-during-covid-19-epidemic/?utm_source=Hackaday.com&utm_campaign=0db272c373-EMAIL_CAMPAIGN_2020_02_26_04_27_COPY_01&utm_medium=email&utm_term=0_a428253bfe-0db272c373-160863683&mc_cid=0db272c373&mc_eid=0cbb6f04e0)
- [Corona Virus Tech Handbook](https://coronavirustechhandbook.com/hardware ) - Useful information about everything corona virus including hardware
- [Uk companies producing ventilators](https://news.sky.com/story/coronavirus-extraordinary-uk-effort-to-produce-thousands-more-ventilators-11961559)

## Other Respirator projects
### Open Source Teams
- [Trevor Smale](https://gitlab.com/TrevorSmale/OSV-OpenLung)
- [Cave Dave](https://github.com/cavedave/TogRespirator)
- [Project Open Air](https://www.projectopenair.org/)
- [Low-Cost Open Source Ventilator or PAPR](https://github.com/jcl5m1/ventilator)
- [The pandemic ventilator](https://www.instructables.com/id/The-Pandemic-Ventilator/)
- [John Strupat Pandemic Ventilator](https://www.cbc.ca/news/canada/london/pandemic-ventilator-coronvirus-hospitals-1.5493830)
- [Isinnova Snorkelig Ventilator mask](https://www.isinnova.it/easy-covid19-eng/?fb-edit=1)
- [Another Team doing the MIT ventilator](https://github.com/RuairiSpain/openVentilator)
- [Oxvent from the University of Oxford and King’s College London](https://oxvent.org/)
- [Ocygen Protofy](https://www.oxygen.protofy.xyz/)

### Lebanese teams
- [Lebanese Response Team](https://lebanonresponseteams.info/)
- Phoenix Machinery
- [I Network Automation](http://yasour.org/2018/ar/news/details/news-35198?fbclid=IwAR3qMfYjVbswqOuwGkewS36E6zfc6WpJ9vpqZufsBHL1xw7cv4Iw0X7pPZc)

## Maker Spaces
- [Berytech Fablab](https://berytech.org/offices/fablab/) in Lebanon is sponsoring makers to fight Covid19

## Academic & Professional Societies & Patents Information
- [MIT mechanical ambubag ventilator project](https://web.mit.edu/2.75/projects/DMD_2010_Al_Husseini.pdf)
- [American Thoracic Society Explanation about Mehchanical Ventilation](https://www.thoracic.org/patients/patient-resources/resources/mechanical-ventilation.pdf)
- [Optimal Ventilator Settings](https://journals.lww.com/ejanaesthesiology/fulltext/2008/02000/optimal_ventilator_settings_in_acute_lung_injury.1.aspx)
- [Ambu-bag automation system and method](https://patents.google.com/patent/US20110041852A1/en)

## Professional Respirators
- [Ventisim a ventilator simulator for training healthcare professionals](https://www.ventisim.com)
- [Hamilton Medical](https://www.hamilton-medical.com/en/)
- [Airvo2 humidifier](https://www.fphcare.com/us/hospital/adult-respiratory/optiflow/airvo-2-system/)
- [One Breath](http://www.onebreathventilators.com/) - a Stanford startup to make ventilators

