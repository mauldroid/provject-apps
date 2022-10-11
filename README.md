# provject-apps

# Project Directory
1. [L2VPN CONFIG GENERATOR](https://github.com/mauldroid/provject-apps#1-l2vpn-config-generator)

2. [INITIAL CPE GENERATOR](https://github.com/mauldroid/provject-apps#2-initial-cpe-generator)


# 1. L2VPN CONFIG GENERATOR
###### by ulma

## PROJECT GUIDANCE

- Collect topology technical data
- Verify vlan on all path
- Verify RDID in RR MPLS MTI
- Input verified technical data to apps
- Generate result
- Export generated config (Optional) 

## PROJECT TASKLIST

- [x] Write Project Readme :ok:
- [x] Create GUI :ok:
- [x] Create ASR9K Support :ok:
- [x] Create Huawei Support :ok:
- [ ] Create ZTE Support :soon:

## CHANGELOG

*************
#### **V1.0 - 300922**

- Application uploaded
*************

*************
#### **V1.1 - 031022**

- Max "nama l2vpn" capped to 16 char
- Add visual placeholder nama l2vpn
- Fixed visual label vpls from "Remote VE-ID" to "Range VE"
*************

*************
####  **V1.2 - 041022**

- Increase "nama l2vpn" cap to 26 char
- Add fixed vlan range 1-4094 (experimental)
*************

*************
####  **V1.3 - 061022** 

- :new: Add zte tab placeholder
- Fixed vlan hierarchy
- Fixed empty vlan fill critical bug
*************

*************
#### :sparkles: **V1.3.1 - 111022 [LATEST RELEASE]** :sparkles:

- fixed combobox function
*************

# 2. INITIAL CPE GENERATOR
###### by ulma

## PROJECT GUIDANCE

### - Application Step
- Collect topology technical data
- Verify vlan management
- Verify IP address management
- Input verified technical data to apps
- Generate result

### - For MikroTik Device
- Upload generated result to device
- Use "import" command

### - For Huawei Device
- Copy and paste entire generated result document into device

## PROJECT TASKLIST

- [x] Write Project Readme :ok:
- [x] Create GUI :ok:
- [x] Create MikroTik Support :ok:
- [ ] Create Huawei Support :soon:

## CHANGELOG

*************
#### **V0.1 - 101022**

- Application uploaded
- Alpha test started
*************