# 5G Fundamentals

## Wireless Communication
 - Allows the transfer of information over the air between the transmitter and reciever
 - Same device acts as both transmitter a transmitter and reciever
   
![image](https://github.com/user-attachments/assets/ea6952bf-02ba-4dff-89c0-d6828a6ad403)

## Radio Frequency (RF)
 - RF is a electromagnetic signal which is characterizd by its wavelength and frequency
 - frequency{3khz - 300ghz}
 - wavelength{100km-1mm}

## Radio signaal properties
- travel at the speed of light ~ 300,000km/sec
  
 ![image](https://github.com/user-attachments/assets/00f286f1-4b7a-4f6a-b171-011c06a351fa)

## Carriers Waves and Modulation
- RF signals used for information transfer also known as carrier waves
- Moulation is which i used to impress information onto carrier wave for transmission
## Analog and Digital Modulation
- digital modulation is used for discrete or binary information represented by bits(0s and 1s)
- analog modulation is used to transfer low b frequency based signal
  ![image](https://github.com/user-attachments/assets/f73593da-ed93-40d3-b7b1-5981a251aee8)

## Noise and interference
- when information is sent over any wireless communication link noise and interference is introduced
- noise - unwanted energy
- interfrence - it is a form of energy 
![image](https://github.com/user-attachments/assets/916dcffa-76bf-44b7-8ae6-a72430563cc9)

## Radio Spectrum
- it simply the range of radio frequencies over which wireless communication takes places dor a specific purpose
- RS of mobile phones - {450MHz to 3800MHz}
- every country has government agencies responsible for its spectrum planning
  ![image](https://github.com/user-attachments/assets/6dca53de-a4da-4187-9bc3-c6eb462447cb)
## Frequency Division Duplexing (FDD)
- mobile system uses fdd
- pair of radio channel for two way communication
- both side can transmit information at the same time on independent links
  ![image](https://github.com/user-attachments/assets/dd2e2d80-06f7-4234-a6d5-9090b42852e3)

  ## Time division duplexity
  - not all radio spectrum is allowed with frequency duplexed links
  - TDD uses a single radio channel for two-way communication by allocating different transmission times for each direction (uplink/downlink)
    
  ![image](https://github.com/user-attachments/assets/444c6fed-9bec-4af5-bb9d-a0dd640926f0)

    ## Radio channel-bandwidth
    - a radio signal that carries information uses a range of frequencies over which communication link is established.
    - radio channel = data pipe
    - wider = more data , narrow = less data
      
   ![image](https://github.com/user-attachments/assets/38d4092a-5338-4e2b-bca8-31ba9d38e5b5)

 - when two adjacent cells use the same radio frequency at the same time , they create interference where the radio coverage overlaps

   
   ![image](https://github.com/user-attachments/assets/9848a3b3-ccf3-4b3e-986f-f5eebfe6e9cd)

## MIMO
 - MULTIPLE INPUT MULTIPLE OUTPUT
 - maximun number of pipes is limited by the minimum of n & m
 - no. of pipes depends on the radio channel

   
![image](https://github.com/user-attachments/assets/f0fcb444-017c-45c6-b6fb-b0d2eff3b0aa)

## cellular concepts
 - coverage area divided into cells
 - each cell is served by a base station
 - cells are designed to have overlapping coverage

   
   ![image](https://github.com/user-attachments/assets/807c2bb6-a1a4-4a79-a1a4-b2d07a4db863)

   ## RAN (Radio Access Network)
 - base stations are interconnected
 - user communicates with one base station at any time

   ![image](https://github.com/user-attachments/assets/403d33fb-0342-46c2-b8f0-31569f594c7b)

   ## Protocols
   - network protocols define an agreed upon set of rules governing the exchange of information
   - two type of information:
-control(aka signaling) - setup , reconfigure , and release the data link
-data (aka traffic) - the actual information o be exchanged

- Protocols re defined in layers(protocol stack)

![image](https://github.com/user-attachments/assets/d0ef0ba4-4e18-4f0e-a9f9-fd1ebc70cba5)

# 1G to 4G 
- 1g - introduced in 1980
- technology introduced - Advanced Mobile Phone System
- 2g - introduced in 1990
- technology introduced - IS-95 and GSM
- 3g - introduced in 2000
- technology introduced - CDMA2000 & WCDMA
- 4G - lte / lte advanced

  ![image](https://github.com/user-attachments/assets/2a2ce8e7-e375-4b04-a2d9-ecd3215a5867)

# LTE

- LTE is long term evolution
- 3GPP defines the specifications for 3g , 4g , 5g

![image](https://github.com/user-attachments/assets/df513911-1572-43dc-aa7e-48e64be1effb)

## key features LTE architecture 

- seprate radio , packet core and services networks
- evolution to common all-ip network
- interoperability with 3g and other wireless network

  ![image](https://github.com/user-attachments/assets/beadf8b4-7973-47cb-94b9-e70d322c45cc)


# E-UTRAN provides users with radio access

 ### evolved node b (enb)
 - radio connection management
 - radio resource allocation

 ![image](https://github.com/user-attachments/assets/63902fbd-bb8b-41e6-8272-10cb324232fd)

 
### mobile management entity (MME)

 - user registration and authentication
 - mobility management subscribers

 ![image](https://github.com/user-attachments/assets/0eb46e1a-9081-4747-80ed-7160de20e4d4)


 ![image](https://github.com/user-attachments/assets/3493593f-d572-4955-90d6-7deb13572faf)


## LTE air interface highlights 

![image](https://github.com/user-attachments/assets/1424346a-19da-4b15-b567-38b1338938c0)

### Duplexing options 
 - Lte allows fdd and tdd transmission
 - fdd provides operators capability to operate uplink and downlink in diferent system bandwidth
 - tdd provides operator greater flexibility specturm utlixation for packet data application

   ![image](https://github.com/user-attachments/assets/865979bc-ab0c-40b4-89c2-93b584f9dbc5)

## scalable bandwidth
- scalable bandwidth allows flexibility with lte deployment based spctrum availability

  ![image](https://github.com/user-attachments/assets/df005c8a-b8e5-434f-9b8c-975c7b73ba2b)

  ## lte data modulation
  - lte support for multiple modulation schemes allows higherv data rate where coverage is good
  - QPSK , 16-QAM , 64-QAM , 256QAM
 
    ![image](https://github.com/user-attachments/assets/d1b61186-ee74-4f83-a516-b78066029a59)

  # MIMO operation
 - support for 2 * 2m 4 * 4 mimo and higher mimo orders 2or4 antennas at enodeb and moile devices
 - single-user mimo can increase a single user throughput by up to 4x
 - multi user mimo can increase the throughput of the enode b

  ![image](https://github.com/user-attachments/assets/3d97f3a6-5202-4bf6-bd85-1b2f3b94015f)

  ## Lte handover and mobility 
  - only one serving cell
  - hard handover based mobility
  - x2 interface between enodesBs

 # LTE operation
 - lte is optimized to deliver packet data services
 - always on connectivity'connection wuth multiple packet data networks

# The EPS bearer is an LTE Data connection
- eps bearer is data pipe connection through the lte network , from the handset to the packet gateway
  
  ![image](https://github.com/user-attachments/assets/d55a39c7-3267-4807-bb92-4efa1aa73f55)


  ![image](https://github.com/user-attachments/assets/b5544c8c-e0a0-491f-9d77-e273a82f5d5a)

  # Access Point Name (APN)

- Apn identifiesthe packet data connection and the services
- one or more apns may be served by a p-gw

  ## How operators provide voice service in 4g ?
  - voice over LTE (voLTE)
  - circuit switched fallback (csfb)
  - voice over wi-fi (vowifi)

  ![image](https://github.com/user-attachments/assets/6243b6ed-4c61-4089-9f75-b78db5248c59)

  ## How does lte advanced imporve perfomance in rel 10
  - air interface changes
    carrier aggregation
    enhanced mimo

  _ system imporvements
   hetrogeneous networks
   small cells

  ![image](https://github.com/user-attachments/assets/bb0f9e30-4331-4e78-949c-10bcc230f219)

  ## Carrier Aggregation
   - two to five "components carriers " (CC) aggregated into larger bandwidth
   - permits use of 100mhz of specturm (5 x 20mhz)
 
     ![image](https://github.com/user-attachments/assets/6a51fcd3-8709-4fff-8230-1348cd7a61ac)

## Enhanced MIMO

- up to 4x4 MIMO on uplink
- up to 8x8 MIMo on downlink
- higher efficiency increased capacity greater throughput

  ![image](https://github.com/user-attachments/assets/76dde17a-b6eb-4e95-9e13-674e9ae1d56c)

## LTE advanced 

- unlicensed band 5ghz band
- typically used for  wifi
- LAA allows carrier aggregation b/w licensed and licensed bands
- free capacity for operators
- govened by usage regulayions

  ![image](https://github.com/user-attachments/assets/67b9d649-6927-4f97-9140-3e063997e611)


  ![image](https://github.com/user-attachments/assets/f0cdd57d-e054-4a24-827c-a0c0ddc5c97a)


  # 5g drivers and motivations


![image](https://github.com/user-attachments/assets/3a4b3023-4f8c-4e6b-bf78-b618d38a8ab6)



![image](https://github.com/user-attachments/assets/a487064b-f69c-4e01-be6e-90648af08dd4)

## 5g network terminology and concepts
 - gNodeB (gnb) - supports the NR as well as connectivity to NGC
 - ng-eNode(ng-eNb) - next generation eNB that supports connectivity to epc and npc
 - access management functions (amf) - supports ue's network access and manages its mobilty
 - session managment function (smf) - support ip address allocation and connectivity

   ![image](https://github.com/user-attachments/assets/b1067502-a1c7-4172-a6c8-ee3c12d7392f)

## 5g nr waveforms
- similar to LTE 5g uses ofdm-based waveforms

  ![image](https://github.com/user-attachments/assets/da94c999-2ce9-4a62-8241-bb588662f8ed)

- massive MIMO
  
-  5g nr employs massive mimo to mitigate the disadvantage of high frequency propagation
-  massive mimo antennas arrays with large no. of elements instrinsically narrow beams

  ![image](https://github.com/user-attachments/assets/69a3d0dc-172a-4699-98bc-128ad0f0d075)

  - beam sweeping
    
  - a narrow beam does not provide coverage over a cell area
  - beam sweepin allows the gnb to periodically steer one narrow beam to cover a ide area

  ![image](https://github.com/user-attachments/assets/b924975a-be24-4c18-aa29-c60681201c86)


## 5g nr architecture 

  ![image](https://github.com/user-attachments/assets/d2af88cc-9c36-4ced-af7e-df412aa8a482)


  ![image](https://github.com/user-attachments/assets/a0cf5b01-cc4b-4c78-9d44-2be3d2cb216c)


  ## NSA 5g NR  accelerating 5g NR deployments

  ![image](https://github.com/user-attachments/assets/ae08923e-7fe0-4685-b791-349377a4671a)

  ## 5g next gen core (ngc) also part of 3gpp release 15

  - configurable end to end connectivity per vertical
  - modular specialized network function per services
  - flexible subscripion model
  - dynamic control and user planes with more functionally at the edge

    ## key networking features
    - nfv - network function vitualization
    - sdn - software defined networking
    - network slicing
    - mec - mobile edge computing
    ### 5g network architecture becomes more :

    - software /hardware seprated
    - cloud driven
    - -programmable
    - easily scalable
    - orchestration flexible
   
      ![image](https://github.com/user-attachments/assets/8e1857d2-48e6-4ae6-965c-c7db8888e913)


      ## Network Functions Vitualization (NFV)
      - nfv aims to transform the way operators architect networks
      - involves the implementation of network functions (NF) in software
      - evolves staandard it virtualization technology to consolidate many networ equipment types onto industry standard high volume servers switches and storage
     
     ### benefits
    - decoupling software from hardware
    - flexible network function deployment
    - dynamic operation
   

      ![image](https://github.com/user-attachments/assets/50dd459c-20e5-4f5d-b001-e7658ac2ff86)


      ## Software Defined Networking (sdn)

      - sdn is an emerging network architecture
      - network control functions/tasks are decoupled from network devices
      - migration of control from individual network devices / boxes into accesible distributed computing/functions
      - undelying infrastructure can be abstracted for different appication and network services


        ### Benefits
          - centralized management and control of network devices
          - rapid innovation on new network capabilities and service
          - incresed network reliability and security
          - more granual network control
       
       ## Network Slicing

      - realizing different network functionalities on the same physical infrastructure meet  varied requirements of different service layers
     
        
        ### benefits
         - efficient resource allocation and utlization
         - control of services
       
           ![image](https://github.com/user-attachments/assets/90d892ad-e009-46ab-aa4f-4257265cc2bb)

## Mobile Edge Computing (MEC)
- mec provides it services and cloud computing at edge of mobile network
- low latency / high bandwidth
- proximity / location awareness
- real time insight into radio network information

      


      




 











   




  














