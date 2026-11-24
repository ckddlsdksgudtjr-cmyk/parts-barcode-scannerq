부품 바코드 외부 스캐너 배포 파일

1. GitHub에서 새 Public repository를 만듭니다. 저장소 이름은 parts-barcode-scanner 권장.
2. 이 폴더의 index.html 파일을 저장소 최상위(root)에 업로드합니다.
3. 저장소 Settings > Pages > Build and deployment에서 Deploy from a branch를 선택합니다.
4. Branch: main, Folder: /(root)를 선택하고 Save합니다.
5. 배포 후 https://깃허브사용자명.github.io/parts-barcode-scanner/ 형태의 주소가 만들어집니다.
6. Apps Script 코드에서 EXTERNAL_SCANNER_URL 값을 그 주소로 바꿉니다.
7. Apps Script 저장 후 배포 관리 > 수정 > 새 버전 > 배포합니다.

스캐너는 HTTPS로 열려야 하며, 재고관리 앱의 '카메라 스캔 시작' 버튼에서 새 창으로 열어야 스캔 결과가 원래 앱으로 전달됩니다.
