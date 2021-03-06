## SARS-CoV-2 Transmission

<p align="center">
<img src="https://github.com/Berger-DM/SARS-CoV-2-and-COVID-19-Process-Models/blob/gh-pages/SARS-CoV-2%20Process%20Models/SARS-CoV-2%20Transmission.jpg" width=50% height=50%>
</p>

The COVID-19 Transmission process can start at any point in the infectious period of the disease for an infected person (*Start Event: Spread begun*). The infected human defines in which form they will spread the virus (*Task: Define form of spread*). The virus can either be spread through direct spread (person to person), or through indirect spread (fomites), or through airborne spread, or through another undefined form of spread.

If the virus is spread through direct spread, then this direct spread can either be through touching, coughing, sneezing, or exhaling. If the virus is spread through touching, then the infected person touches another person with their virus-covered hands (*Task: Touch another person with virus-covered hands*), which leads to infected droplets being deposited on the receiver’s hands (*Intermediate Message Throwing Event: Infected droplets deposited on receiver’s hand*). If the virus is spread through coughing, then the infected human coughs close to another person (*Task: Cough close to another person*); if the virus is spread through sneezing, then the infected human sneezes close to another person (*Task: Sneeze close to another person*); if the virus is spread through exhaling, then the infected human exhales close to another person (*Task: Exhale close to another person*). If the virus is spread through coughing, sneezing, or exhaling, these then lead to infected droplets being launched in the air (*Intermediate
Message Throwing Event: Infected droplets launched in the air*).

If the virus is spread through indirect spread, then this indirect spread can either be through touching, coughing, sneezing, or exhaling. If the virus is spread through touch, then the infected human touches an object or surface with their virus-covered hands (*Task: Touch an object or surface with virus-covered hands*); if the virus spread through coughing, then the infected human coughs over an object or surface (*Task: Cough over object or surface*); if the virus is spread through sneezing, then the infected human sneezes over object or surface (*Task: Sneeze over object or surface*); if the virus is spread by exhaling, then the infected human exhales over an object or surface (*Task: Exhale without covering mouth over object or surface*). In any case, it leads to infected droplets being deposited or a surface or an object (*Intermediate Message Throwing Event: Infected droplets deposited on surface or object*).

If the virus is spread through airborne transmission, then the infected person is subjected to an Aerosol Generating Procedure (AGP) (*Task: Be Subject of Aerosol Generating Procedure*).

If the virus is spread through an undefined form of spread, then the infected human spreads it with an undefined action (*Task: Spread through undefined action*). After that, the virus is spread through undefined means (*Intermediate Message Throwing Event: Virus transmitted via undefined means*).

In any of these cases, the process ends when the virus is spread (*End Event: Virus spread*).
