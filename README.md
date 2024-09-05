## 1. 회원 가입

외국 결제 가능 카드로만 회원 가입이 가능합니다.

[회원 가입 링크](https://azure.microsoft.com/ko-kr/free/search/?ef_id=_k_Cj0KCQjwiuC2BhDSARIsALOVfBLRVW7Al-hagClGdo3WPheZ1GAPsydfHxE-qUVBq3XfoD3F8zP47ecaAnuEEALw_wcB_k_&OCID=AIDcmmmbxccejx_SEM__k_Cj0KCQjwiuC2BhDSARIsALOVfBLRVW7Al-hagClGdo3WPheZ1GAPsydfHxE-qUVBq3XfoD3F8zP47ecaAnuEEALw_wcB_k_&gad_source=1&gclid=Cj0KCQjwiuC2BhDSARIsALOVfBLRVW7Al-hagClGdo3WPheZ1GAPsydfHxE-qUVBq3XfoD3F8zP47ecaAnuEEALw_wcB)

## 2. VM 생성

1. **가상 머신 생성 페이지 접속**  
   아래 링크를 통해 Azure 포털에서 가상 머신 생성 페이지에 접속합니다.  
   [가상 머신 생성 링크](https://portal.azure.com/#browse/Microsoft.Compute%2FVirtualMachines)

2. **가상 머신 선택 및 설정**  
   - "Azure 가상 머신"을 선택합니다.  
![image](https://github.com/user-attachments/assets/9a99d3dd-568e-498a-9023-acab5e8c2372)

   - 가상 머신의 이름, 지역, 이미지 등을 적절히 설정합니다. 
![image](https://github.com/user-attachments/assets/72edccd8-352d-4f4f-beb3-1ffd6b40b515)

   - 이미지 선택 시 운영체제를 선택할 수 있으며, 운영체제에 따라 요금이 다를 수 있습니다.   
   - 예를 들어, CentOS 7은 요금이 상대적으로 비쌉니다.  


3. **관리자 계정 설정**  
   - 관리자 계정의 인증 형식을 "암호"로 설정하고 적절히 기입합니다.  
![image](https://github.com/user-attachments/assets/37c7af12-bc68-48f6-a19c-859bfb54922c)


4. **네트워킹 및 검토**  
   - 네트워킹 탭으로 이동하여 가상 네트워크와 서브넷을 기본값으로 선택한 후, "검토 + 만들기" 탭으로 이동하여 VM 생성을 완료합니다.
![image](https://github.com/user-attachments/assets/0212e7a8-8203-4455-9fba-74ba0a06a866)


5. **접속 및 네트워크 설정**  
   - VM 생성이 완료되면 MobaXterm을 사용하여 VM에 접속할 수 있습니다.  
   - TCP/IP 통신을 위해 VM의 네트워크 설정 탭에서 인바운드 및 아웃바운드 규칙을 추가해야 합니다.  
![image](https://github.com/user-attachments/assets/91fbd16f-13ca-4fb9-8f14-1bb513b485b8)

   - 추가한 후 필요한 설정을 완료합니다.

## 3. SmartGuard Test
사내 정보입니다.
