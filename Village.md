# Village 프로젝트 ( 공간 대여 )

![village-sample](https://github.com/clean17/clean17.github.io/assets/118657689/2aef4ac3-8c93-4a97-997a-30290b98f5ce)

> ## 프로젝트 소개

- 주변에서 춤 연습을 하거나 회의를 하거나 공부를 하려는 등의 공간을 알아보고 있나요 ? <br>
- 여러분에게 필요한 여러 공간을 여기서 빌려보세요 !<br>
- 호스트는 공간을 등록하고 사용자는 예약, 결제를 통해 공간을 빌리는 서비스 입니다.

<br>

> ## 기술 스택

### 개발 툴<br>

![image](https://github.com/clean17/Village-Front-Project/assets/118657689/c0ebe32a-0db1-4b6e-8e3a-7744ad702753)

### 사용 언어<br>
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/272a1dca-de7f-4e0d-85e2-7713799e7790)

### DB<br>
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/a439e899-0ceb-44b5-9f88-2f648a31128f)
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/546e397b-2d5a-4f70-b3f4-d6a46e1f8d7d) <br>

### 프레임워크<br>
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/11426330-7c5f-4fd1-b0f4-16f30896867d) <br>

### 사용 기술<br>

![image](https://github.com/clean17/Village-Front-Project/assets/118657689/6dc90d44-5af6-474b-b922-eb4e92bdad2e)
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/8d72bc2e-fbc0-4f3c-baa7-8950fab14bd3)
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/5841bee3-7aeb-4d1e-854b-07dce6bbeb29) <br>
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/7abd71a4-eaa6-4f64-aa81-51a3f4f64dc2)
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/040adecc-389d-4c38-b563-9b51ee2eb5ac)
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/ce3d2df9-4d06-4df8-9482-f5b98f2bb44a)
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/dd60862c-fa66-4dcd-b035-4be6f7507544)
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/e33f02cb-6fae-4c53-901a-89d386693ac4)<br>

### 협업 툴<br>
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/70a49178-6bb3-4136-9241-feb5a0663f23)<br>
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/7fa02c32-4862-4391-97a9-b446b52f7150)
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/30dccaf8-feff-459c-bb32-c7e857141b6b)<br>
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/4da6dc79-8bda-4c09-af7d-ab38e7179191)

### 기타 툴<br>
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/44f52fdb-b6db-45cc-a58d-4b35289db93c)

### 협업 방식<br> 
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/70a49178-6bb3-4136-9241-feb5a0663f23)<br>
![img_8.png](image/img_8.png)
```
figma : 디자인을 공유하고 피드백을 주고 받을 수 있습니다.
```
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/7fa02c32-4862-4391-97a9-b446b52f7150)
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/30dccaf8-feff-459c-bb32-c7e857141b6b)<br>
![img_6.png](image/img_6.png)<br>
```
Git-hub : 이슈를 이용하여 협업을 하여 오류를 기록하여 지난 오류 로그를 한눈에 볼 수 있고, 팀원들의 이슈를 확인하여 협업을 할 수 있습니다.
```
![img.png](img.png)<br>
```
pull-request를 이용하여 협업을 하여 코드를 리뷰하고, 코드를 수정할 수 있습니다.
```
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/4da6dc79-8bda-4c09-af7d-ab38e7179191)
![img_5.png](image/img_5.png) <br>
```
Notion : 프로젝트 일정 관리 및 회의록을 작성할 수 있습니다.
```

> ## 내가 한 기능

> ## FCM : Firebase Cloud Messaging - 구글제공 클라우드 메시징 서비스
> ![img_2.png](image/img_2.png) <br>

예약 및 결제시 Firebase의 FCM을 이용하여 앱으로 알림기능을 구현 <br>
- FCM을 사용한 이유는 실시간으로 데이터 전송을 지원을 하여 사용자(Host)에게 빠르게 알림을 전송할 수 있기에 사용<br>
- 앱을 처음 킬 때 firebase에 요청을 하여 토큰을 받고 앱에서 서버로 토큰을 보내면 서버에서 firebase로 토큰을 검증하고
검증이 됐다면 DB에 저장을 시켜 토큰 값을 보관<br>
- 로그인 시 토큰을 받아와서 FCM 테이블에 사용자의 id를 업데이트 시킴 
- 저장된 FCM 토큰을 이용하여 사용자들에게 알림을 보냄

요청을 할 때의 loginDTO
```java
public static class LoginDTO {
    
    ...
    
    private String targetToken;
    }
```

#### 토큰을 DB 에 저장 시키기
```java
@PostMapping("/fcm/token")
    public ResponseEntity<?> pushMessage(@RequestBody String token) throws Exception {

        if (token != null) {

            Fcm fcm = new Fcm();
            String targetToken = token.split("=")[1];

            Optional<Fcm> targetTokenOptional = fcmRepository.findByTargetToken(targetToken);

            if (targetTokenOptional.isEmpty()) {
                fcm.setTargetToken(targetToken);
                fcmRepository.save(fcm);
            }
        ...
    }
```
- 앱 실행시 전달 되는 토큰을 받아와서 DB에 저장<br>

#### 로그인 시 FCM 테이블에 User 업데이트 시키기

```java
        ...
        // User가 로그인 시 FcmToken 같이 넣기
        Optional<Fcm> fcmTokenOptional = fcmRepository.findByTargetToken(loginDTO.getTargetToken());
        if (fcmTokenOptional.isEmpty()){
        throw new CustomException("해당 토큰이 존재하지 않습니다");
        }

        Fcm fcmToken = fcmTokenOptional.get();

        Optional<User> userOptional = userRepository.findById(loginViewDTO.getId());
        if (userOptional.isEmpty()){
        throw new CustomException("유저를 조회할 수 없습니다.");
        }

        User user = userOptional.get();

        fcmRepository.save(fcmToken.toEntity(fcmToken.getId(), user, loginDTO.getTargetToken()));
                ...
        }
```
- Fcm 테이블에서 사용자의 토큰 값을 조회를 해서 토큰 값이 없으면 예외처리를 함<br>
- 토큰이 값이 있을 때는 해당 토큰을 DB에 저장된 토큰과 비교하여 같으면 User의 데이터를 업데이트 시킴<br>

#### 토큰을 활용하여 해당 사용자에게 알림 보내는 방법
- 사용자 앱 실행 시 푸시 알림을 받을 수 있는 토큰을 생성 
- 토큰을 생성하고 DB에 저장
- 알림을 보낼 때 title과 content 데이터를 준비하고 토큰을 가지고 firebase에 전송
- firebase에서는 토큰을 확인하고 해당 토큰을 가진 앱에게 알림을 전송

```java
public void sendMessageTo(String targetToken, String title, String body) throws IOException {
        String message = makeMessage(targetToken, title, body);

        OkHttpClient client = new OkHttpClient();
        RequestBody requestBody = RequestBody.create(message, MediaType.get("application/json; charset=utf-8"));
        Request request = new Request.Builder()
                .url(API_URL)
                .post(requestBody)
                .addHeader(HttpHeaders.AUTHORIZATION, "Bearer " + getAccessToken())
                .addHeader(HttpHeaders.CONTENT_TYPE, "application/json; UTF-8")
                .build();
        Response response = client.newCall(request)
                .execute();

    }
```
- 예약신청 및 결제신청 할 때 위의 과정을 이용해서 HOST에게 알림을 보내는 기능 구현 <br>
 
> ## AWS S3 - 아마존 웹 서비스의 클라우드 스토리지 서비스
> ![img_9.png](image/img_9.png) <br>

```java
// file s3에 저장
  List<File> fileList = new ArrayList<>();

  for (FileSaveDTO.FileSaveDto files : placeRequest.getFile()) {
      String imgPath = s3Service.upload(files.getFileName(), Base64Decoded.convertBase64ToMultipartFile(files.getFileUrl()));
      files.setFileUrl(image/imgPath + ".jpg");

      File save = fileRepository.save(files.toEntity(files.getFileName(), files.getFileUrl(), place));
      fileList.add(save);

      fileService.save(placeRequest.getFile().get(0));
            }
```
#### 파일을 AWS S3 버킷에 저장하는 과정

- AWS SDK 를 이용하여 s3(AWS) 에 업로드 한 후 결과를 url로 받음 <br>
- S3에 저장된 이미지 파일의 URL을 DB에 저장
- DB에 저장된 이미지 파일의 URL을 앱으로 전달하고 앱에서 URL을 통해 파일을 불러옴
- 이때 URL은 Base64로 인코딩하여 앱에 전달됨
- 앱에서 Base64로 인코딩된 이미지 파일을 디코딩하여 이미지 파일을 불러옴
- 파일은 그냥 그대로 DB에 넣어 사용을 할 수 있는데 S3를 사용하는 이유는 ?? <br>
-> DB에 파일을 저장하면 파일 크기에 제한이 있기에 DB성능에 영향을 줄 수 있다. <br>
-> 안정적이고 신뢰할 수 있는 서비스로 인정받고 있어 사용을 했고 용량이 가득차면 자동으로 확장되어 유연하게 대응할 수 있다는 점에서 사용 <br>

> ## BootPay - 한국의 온라인 결제 서비스 플랫폼
결제 모듈은 간편한 결제 플로우를 지닌 부트페이를 사용했고 결제 검증을 하여 부적절한 요청이 왔을 때 해결 <br>
- 앱에서 결제를 시도 할 때 받아오는 request 데이터를 1차적으로 DB에 주문 아이디, 주문 이름, 가격 저장

```java
public Payment 결제검증(PaymentDTO paymentDTO) {
        paymentDTO.setStatus(PaymentStatus.WAIT);
        return paymentRepository.save(new Payment(paymentDTO.getOrderId(), paymentDTO.getOrderName(), paymentDTO.getPrice()));
    }
```

- 결제 서버 승인 시, 부트페이 웹훅으로 결제 정보를 받아와서 DB에 저장된 데이터와 비교를 하여 결제할 수량과 가격 검증을 한후 정상 이면 결제 진행 아니면 결제 취소를 진행
```java
public Bootpay 구매요청(ReceiptDTO receiptDTO) {

    Optional<Payment> paymentOptional = paymentRepository.findByOrderIdAndOrderNameAndTotalPrice(receiptDTO.getOrderId(), receiptDTO.getOrderName(), receiptDTO.getPrice());

    if (paymentOptional.isEmpty()) {
        throw new Exception400("payment","결제 정보가 올바르지 않습니다.");
    }

        ...
}
```


> ## Swagger - API 문서화를 위한 오픈소스 프레임워크
> ![img_10.png](image/img_10.png) <br>

1. Spring에 Swagger 적용

build.gradle 에 의존성 추가
```Gradle
implementation 'org.springdoc:springdoc-openapi-ui:1.6.7'
```
2. Swagger UI 접속 방법 <br>
   http://localhost:8080/swagger-ui/index.html#/ <br>
    위의 주소로 접속을 하면 Swagger UI 화면이 나옴 <br>
3. Swagger 어노테이션 종류 및 사용법
![img_11.png](image/img_11.png) <br>
- @Tag : Controller 클래스에 적용하며, Swagger 리소스에 대한 정보를 표현
- @Operation : Controller 메소드에 적용하며, Tag에 대한 세부적인 API에 대한 정보를 표현
  ![img_12.png](image/img_12.png) <br>
- Tag는 위 사진의 빨간 박스에 있는 명칭을 지정을 할 수 있는 것으로 name과 description으로 정리
- Operation 은 파란 박스로 summary와 description으로 정리 가능
4. Swagger UI 화면 정렬<br>
![img_13.png](image/img_13.png) <br>
- 정렬이 되어있지 않은 화면을 정렬을 하기 위해서 Customizing 을 해야함
- 시나리오를 작성하고 정렬을 하기 위해서는 SwaggerConfig 파일을 생성을 해야함
```java
@Bean
public OpenApiCustomiser sortTagsAlphabetically() {
   return openApi -> {
       List<Tag> tags = openApi.getTags()
         .stream()
         .sorted(Comparator.comparing(tag -> StringUtils.stripAccents(tag.getName())))
         .collect(Collectors.toList());
            }
}
```
- 위의 코드는 tag를 정렬하는 코드로 이름 순으로 정렬을 하기 위해서 사용
  ![img_14.png](image/img_14.png) <br>
- 위의 코드를 작성하고 Swagger UI 화면을 보면 정렬이 되어있는 것을 확인 할 수 있음

```java
Paths sortedPaths = new Paths();

  Map<String, PathItem> paths = openApi.getPaths();
  List<Map.Entry<String, PathItem>> entryList = new LinkedList<>(paths.entrySet());
  List<Map.Entry<String, PathItem>> sortList = entryList
          .stream()
          .sorted(
              Comparator.comparing(
                map -> {
                    PathItem pathItem = map.getValue();
                    if (pathItem.getGet() != null) {
                        if (pathItem.getGet().getSummary() == null) {
                            return nullSortValue;
                        }
                        return StringUtils.stripAccents(pathItem.getGet().getSummary());
                    } else if (pathItem.getPost() != null){
        ...
                    } else if (pathItem.getPut() != null){
        ...
                    } else if (pathItem.getDelete() != null){
        ...
                    } else {
                        return nullSortValue;
                    }
                }
```
- 위의 코드는 Controller 메서드의 Operation 을 정렬하는 코드로 summary를 기준으로 정렬을 하기 위해서 사용<br>
- 이 상황에서 GET, POST, PUT, DELETE 메서드를 사용하고 있기 때문에 각각의 메서드를 정렬을 해야함
- @ApiOperation(value = "GET 메서드", method = "GET") 이 어노테이션을 메서드에 적용을 하면 정렬이 됨
<br>![img_15.png](image/img_15.png) <br>
- 위의 사진 처럼 정렬이 되어있는 것을 확인 할 수 있음


> ## Restdocs - Restful API 문서화를 돕는 기술
> ![img_4.png](image/img_4.png) <br>

통합 테스트를 작성하여 Restdocs 를 이용하여 API 문서화를 시켜 봄 <br>
- swagger 와 restdocs 는 똑같이 API 문서화를 시키지만 Restdocs 를 사용한
가장 큰 이유라고 하면 통합테스트를 이용하여 Controller 의 에러를 잡을 수 있고 효율적으로 문서화를 할 수 있었기에 사용  <br>
- Swagger UI를 통해 상호작용 가능한 API 문서를 제공하며, 클라이언트가 API 요청을 테스트하고 통신할 수 있도록 지원
- restdocs 는 테스트 기반으로 API 를 테스트하면 API 코드와 문서가 함께 유지되므로, API 의 동작과 관련된 정보를 쉽게 확인 할 수 있고 백엔드 에서 작업을 할 때 API 코드를 작성하면서
  동시에 문서도 작성 할 수 있음 <br>
- swagger 의 단점을 restdocs 를 사용하면서 극복한 점 : 테스트 케이스를 실행하여 실제 동작하는 API 와 일치하는 정확한 문서를 생성
- 테스트 코드에서 사용한 요청과 응답에 대한 문서 템플릿 작성 Asciidoctor 문법을 사용하여 문서를 스타일링 하고 필요한 형식을 출력 (markdown 도 사용가능) <br>

```java
@SpringBootTest
@ExtendWith({RestDocumentationExtension.class, SpringExtension.class})
@TestInstance(TestInstance.Lifecycle.PER_CLASS)
public class AbstractIntegrated {

    protected MockMvc mockMvc;
    protected final ObjectMapper objectMapper = new ObjectMapper();

    @BeforeEach
    void setUp(WebApplicationContext webApplicationContext, RestDocumentationContextProvider restDocumentation) {

        this.mockMvc = MockMvcBuilders.webAppContextSetup(webApplicationContext)
                .apply(documentationConfiguration(restDocumentation))
                .apply(SecurityMockMvcConfigurers.springSecurity())
                .build();
    }
```

- 테스트 코드를 작성할 때 @ExtendWith({RestDocumentationExtension.class}) 를 사용하여 Restdocs 를 사용하겠다고 선언
- @ExtendWith({SpringExtension.class}) 를 사용하여 Spring TestContext Framework와 Junit5와 통합하여 사용
- @BeforeEach 를 사용하여 테스트 코드를 실행하기 전에 setUp 실행 <br>
-> @BeforeEach를 사용한 이유는 테스트 코드를 실행하기 전에 mockMvc를 생성하고 문서화를 하기 위해서 사용
- setUp 메서드에서 MockMvc 를 사용하여 mockMvc 를 생성
- mockMvc 를 생성할 때 RestDocumentationContextProvider 를 사용하여 문서화를 하겠다고 선언<br>
-> 테스트 코드에서 생성된 문서의 저장 위치, 문서에 대한 메타데이터, 문서의 형식 등을 정의하고 사용 가능 
- mockMvc 를 생성할 때 documentationConfiguration(restDocumentation) 를 사용하여 문서화를 하겠다고 선언<br>
-> MockMvc를 구성할 때 REST Docs의 구성을 적용하여 테스트를 실행하고, 테스트 결과를 문서화하는 데 필요한 동작을 수행 
- mockMvc 를 생성할 때 SecurityMockMvcConfigurers.springSecurity() 를 사용하여 Spring Security 를 사용하겠다고 선언


> ## 기능정리
- 등록된 공간 목록 조회
- 키워드로 특정한 공간 조회
- 카테고리 검색 조회
- 내 주변 지도에서 등록된 공간 조회
- 로그인된 유저로 공간 예약
- 호스트가 승인하면 공간 결제(BootPay)
- 일반 유저의 호스트 신청
- 호스트의 공간 등록 기능
- 예약 및 결제 내역 확인
- 예약이나 결제시 호스트에게 FCM 알림
- 관리자가 호스트 신청 관리
- 관리자가 등록된 공간, 유저, 예약, 결제를 모두 관리

<br>

> ## 테이블 모델링

<br>

### User 관련 테이블
![img_18.png](image/img_18.png)!
### Place 관련 테이블
![img_17.png](image/img_17.png)
<br>

> ## 구현 화면
#### 메인화면 <br>
![Honeycam 2023-05-10 20-10-34](https://github.com/clean17/Village-Front-Project/assets/118657689/bb4efc0f-4f8f-4f29-a8cd-bfa5a434e82e)
```java
    @GetMapping("/places")
    public ResponseEntity<Page<PlaceDTO>> getPage(Pageable pageable) {
        Page<Place> page = placeService.getPage(pageable);
        List<PlaceDTO> content = page.getContent().stream().map(Place::toDTO).toList();

        return ResponseEntity.ok(new PageImpl<>(content, pageable, page.getTotalElements()));
    }
```
#### Pageable 을 사용한 이유
- 정렬된 데이터를 조회
- DB에서 페이징 쿼리를 자동으로 생성하고 결과를 페이지 단위로 가져올 수 있음
- 페이징을 따로 사용하지 않아도 페이지들의 정보를 받아 올 수 있기 때문에 사용
#### Pageable 의 종류
- Pageable : 페이지 정보를 담고있는 객체
- Page : 페이지 정보를 담고있는 객체
- PageImpl : 페이지 정보를 담고있는 객체

#### 지도 <br>
![Honeycam 2023-05-10 20-11-08](https://github.com/clean17/Village-Front-Project/assets/118657689/76fa9d22-011e-46f9-93dd-5d1774780257)
```java
    @GetMapping("/imageUrl") //쿼리스트링으로 받기
    public ResponseEntity<Map<String, String>> getMapImageUrl(
            @RequestParam double lat, @RequestParam double lng, @RequestParam int zoom
    ) {
        try {
            // Google Maps Static API endpoint
            String url = "https://maps.googleapis.com/maps/api/staticmap";

            // 요청 파라미터
            String parameters = String.format(
                    "center=%f,%f&zoom=%d&size=400x400&markers=color:red%%7Clabel:%%7C%f,%f&key=%s",
                    lat, lng, zoom, lat, lng, "AIzaSyDmvb-5cgAOEvdoYoPt0jDUmxLpsW5aNvg" //api키
            );
            ...
        }
    }
```
- Google Maps Static API의 엔드포인트 URL을 이용하여 지도 이미지를 가져옴
- 쿼리스트링으로 위도, 경도, 줌 값을 받아와서 지도 이미지를 가져옴
- requestUrl 변수에는 완성된 요청 URL을 할당, 요청 URL은 url과 parameters를 결합하여 생성
#### 회원 가입<br>
![Honeycam 2023-05-10 20-12-05](https://github.com/clean17/Village-Front-Project/assets/118657689/c2800454-1a99-43cd-8ad8-18320145039c)

#### 비밀번호 암호화 시켜 회원가입
```java
    public UserResponse.JoinDTO 회원가입(UserRequest.JoinDTO joinDTO) {
        try {
            // select
            String rawPassword = joinDTO.getPassword();
            String encPassword = passwordEncoder.encode(rawPassword); // 60Byte
            ...
        }
    }
```

#### 회원가입 시 Vaild Check
- 회원가입 시 입력한 값이 유효한지 검사
- 유효하지 않은 값이 들어오면 예외를 발생시킴
- 예외가 발생하면 예외 처리를 해줌

#### UserController
```java
    @PostMapping("/join")
    public ResponseEntity<ResponseDTO<?>> join(@RequestBody @Valid UserRequest.JoinDTO joinDTO, Errors Errors) {
       if (Errors.hasErrors()) {
            throw new CustomException(Objects.requireNonNull(Errors.getFieldError()).getDefaultMessage());
        }
        ...
    }
```
#### Vaild
- @Valid 어노테이션을 사용하여 검사
- Errors 객체를 사용하여 예외를 발생시킴
- Errors 객체는 @Valid 어노테이션을 사용한 객체 바로 뒤에 위치해야 함
#### JoinDTO
```java
    public static class JoinDTO {
        @NotEmpty(message = "name을 입력해주세요.")
        private String name;
        @Email(message = "유효한 email 형식이 아닙니다.")
        @NotEmpty(message = "email을 입력해주세요.")
        private String email;
        @NotEmpty(message = "password 입력해주세요.")
        private String password;
```
#### Valid Check Annotation
- @NotEmpty : null 과 "" 둘다 허용하지 않음
- @NotBlank : null 과 "" 둘다 허용하지 않음, 공백도 허용하지 않음
- @NotNull : null 만 허용하지 않음
- @Email : 이메일 형식만 허용

#### 로그인<br>
![Honeycam 2023-05-10 20-12-21](https://github.com/clean17/Village-Front-Project/assets/118657689/7e012423-8b12-4f9d-83c5-6c61feafda38)

#### UserService
```java
@Transactional
public ArrayList<String> 로그인(UserRequest.LoginDTO loginDTO) {
    
    ArrayList<String> loginViewList = new ArrayList<>();

    Optional<User> userOP = userRepository.findByEmail(loginDTO.getEmail());
    if (userOP.isPresent()) {
        User userPS = userOP.get();

        if (passwordEncoder.matches(loginDTO.getPassword(), userPS.getPassword())) {
            String jwt = MyJwtProvider.create(userPS);
            loginViewList.add(jwt);
            loginViewList.add(String.valueOf(userPS.getId()));
            loginViewList.add(userPS.getName());
            loginViewList.add(userPS.getEmail());
            loginViewList.add(userPS.getRole());

            return loginViewList;
    }
```
- 로그인을 할 때 ArrayList에 jwt, id, name, email, role을 담아서 반환

#### UserController
```java
@PostMapping("/login")
    public ResponseEntity<?> login(@RequestBody @Valid UserRequest.LoginDTO loginDTO, Errors Errors) {

        ArrayList<String> loginViewList = userService.로그인(loginDTO);

        String jwt = (String) loginViewList.get(0);
        UserResponse.LoginDTO loginViewDTO = new UserResponse.LoginDTO(Long.parseLong(loginViewList.get(1)) ,
                (String) loginViewList.get(2), (String) loginViewList.get(3), (String) loginViewList.get(4));

        ...
        
        return ResponseEntity.ok().header(MyJwtProvider.HEADER, jwt).body(responseDTO);
    }
```
- 로그인 시 Jwt 토큰 받아서 header에 넣어줌
#### 공간 예약<br>
![Honeycam 2023-05-10 20-15-04](https://github.com/clean17/Village-Front-Project/assets/118657689/329ee29d-799f-4939-8f72-411b50263efc)
![Honeycam 2023-05-10 20-15-20](https://github.com/clean17/Village-Front-Project/assets/118657689/3f8833bf-61e2-4d2e-8031-06ef1ff71603)

```java
@PostMapping("/user/reservation")
    public ResponseEntity<ResponseDTO<ReservationSaveResponse>> save(
            @Valid @RequestBody ReservationSaveRequest reservationSaveRequest,
            @AuthenticationPrincipal MyUserDetails myUserDetails
            ) throws IOException {
            
        ...
        
        var saveReservation = reservationService.예약신청(reservationSaveRequest, myUserDetails.getUser(), place);

        LocalDate date = DateUtils.fromLocalDateTime(DateUtils.parseLocalDateTime(reservationSaveRequest.getDate()));

       ...
    }
``` 
LocalDateTime 으로 들어오는 요청 데이터를 LocalDate 타입으로 파싱하여 받아 예약 신청
#### FCM 알림<br>
![Honeycam 2023-05-10 20-15-37](https://github.com/clean17/Village-Front-Project/assets/118657689/5ebc8f0d-4b22-46bc-aea3-6604648b4811)
<br> 

#### 앱 화면으로 이동하는 코드
```java
 public void sendMessageTo(String targetToken, String title, String body) throws IOException {
    String message = makeMessage(targetToken, title, body);

    OkHttpClient client = new OkHttpClient();
    RequestBody requestBody = RequestBody.create(message, MediaType.get("application/json; charset=utf-8"));
    Request request = new Request.Builder()
            .url(API_URL)
            .post(requestBody)
            .addHeader(HttpHeaders.AUTHORIZATION, "Bearer " + getAccessToken())
            .addHeader(HttpHeaders.CONTENT_TYPE, "application/json; UTF-8")
            .build();

    Response response = client.newCall(request)
            .execute();
}
```

#### 알림 이미지
![img_3.png](image/img_3.png) <br>
- targetToken : fCM 토큰 값 (앱을 설치한 사용자의 기기를 식별하는 토큰 값)
- Title : 제목 (빨간 네모와 같이 제목을 알림창에 표시)
- Body : 내용 (파란 네모와 같이 내용을 알림창에 표시)
#### 예약 신청 시 RequestDTO를 통해 예약 정보를 전달

```java
RequestDTO requestDTO = new RequestDTO("Village",
        "[예약알림]\n"+ user.getName()+ "님이 [" + place.getTitle() + "]에 예약 신청했습니다.\n"
                +"날짜: "+date+"\n"
                +"일시: "+DateUtils.parseLocalDateTime(reservationSaveRequest.getStartTime()).toLocalTime()+"~"
                +DateUtils.parseLocalDateTime(reservationSaveRequest.getEndTime()).toLocalTime()+"\n"
                +"인원: "+reservationSaveRequest.getPeopleNum()+"명\n",
        fcm.getTargetToken());

firebaseCloudMessageService.sendMessageTo(
        requestDTO.getTargetToken(),
        requestDTO.getTitle(),
        requestDTO.getBody());
```

#### 결제<br>
![Honeycam 2023-05-10 20-16-01](https://github.com/clean17/Village-Front-Project/assets/118657689/7a3cf849-09d2-4b24-a9b6-524139f01743)
![Honeycam 2023-05-10 20-16-16](https://github.com/clean17/Village-Front-Project/assets/118657689/2128be34-99b1-4b91-98b5-aba3520354b6)
#### 결제 검증
```java
    @PostMapping("/verification")
    public ResponseEntity<?> compare(@RequestBody PaymentDTO paymentDTO){
        Payment payment = paymentService.결제검증(paymentDTO);
        return new ResponseEntity<>(new ResponseDTO<>(1, 200, "결제 요청 전 DB 넣기 완료", payment), HttpStatus.OK);
    }
```
- 앱에서 결제 요청을 보내면 결제 검증을 위해 결제 정보를 PaymentDTO에 담아서 전달
- PaymentDTO를 통해 결제 검증을 하고 결제 정보를 Payment에 담아서 반환
- 결제 검증이 완료되면 결제 정보를 DB에 저장
- 결제 검증이 완료되면 결제 정보를 Payment에 담아서 반환<br>
![Honeycam 2023-05-10 20-16-27](https://github.com/clean17/Village-Front-Project/assets/118657689/7efd754d-3723-427c-98ff-accf00c1b63e)



#### 구매 요청
```java

    @PostMapping
    public ResponseEntity<HashMap<Object,Object>> save(
            @RequestBody ReceiptDTO receiptDTO
            , @AuthenticationPrincipal MyUserDetails myUserDetails) throws IOException {

        objectMapper.writeValueAsString(receiptDTO);

        paymentService.구매요청(receiptDTO);

        ...
    }
```

#### 구매요청 Service
```java
    @Transactional
    public Bootpay 구매요청(ReceiptDTO receiptDTO) {

        Optional<Payment> paymentOptional = paymentRepository.findByOrderIdAndOrderNameAndTotalPrice(receiptDTO.getOrderId(), receiptDTO.getOrderName(), receiptDTO.getPrice());

        if (paymentOptional.isEmpty()) {
            throw new Exception400("payment","결제 정보가 올바르지 않습니다.");
        }

        Payment payment = paymentOptional.get();

        payment.setStatus(PaymentStatus.COMPLETE);
        paymentRepository.save(payment);

        ...
    }
```
- findByOrderIdAndOrderNameAndTotalPrice() 메서드를 통해서 DB에 들어 있는 값이 다르면 결제 정보가 올바르지 않다는 예외를 발생시킴
- 결제 정보가 올바르면 결제 상태를 COMPLETE로 변경
#### HOST 신청<br>
![Honeycam 2023-05-10 20-17-07](https://github.com/clean17/Village-Front-Project/assets/118657689/111e4c46-6959-4a39-a244-601bcb7c230d)
![Honeycam 2023-05-10 20-17-16](https://github.com/clean17/Village-Front-Project/assets/118657689/b5167c25-8625-43dd-a763-a9cd60e1d93f)

#### HOST 신청 DTO Vaild Check
```java
public class HostSaveRequest {

    @NotBlank(message = "호스트의 이름을 다시 확인해주세요.")
    private String hostName;

    private String nickname;

    @NotBlank(message = "호스트의 주소를 다시 확인해주세요.")
    private PlaceAddress address;

    @NotBlank(message = "호스트의 사업자 번호를 다시 확인해주세요.")
    @Size(min = 10, max = 10, message = "사업자 번호는 10자리여야 합니다.")
    private String businessNum;

    private HostStatus status;
}
```
- @Size를 사용하여 사업자 번호의 길이를 10자리로 제한
- @NotBlank를 사용하여 빈 값이 들어오면 예외를 발생시킴

HOST 신청을 하면 status를 Wait로 변경
```java
public Host 호스트신청(HostSaveRequest hostSaveDto) {

        ...

        Host host = hostRepository.findByUserId(user.getId());
        host.setStatus(HostStatus.WAIT);

        ...
}
```

#### 공간 등록<br>
![Honeycam 2023-05-10 20-17-36](https://github.com/clean17/Village-Front-Project/assets/118657689/efd332c4-f67f-482e-9314-e53deb671752)
#### 이미지 AWS S3로 전송

```java
// file s3에 저장
  List<File> fileList = new ArrayList<>();

  for (FileSaveDTO.FileSaveDto files : placeRequest.getFile()) {
      String imgPath = s3Service.upload(files.getFileName(), Base64Decoded.convertBase64ToMultipartFile(files.getFileUrl()));
      files.setFileUrl(image/imgPath + ".jpg");

      File save = fileRepository.save(files.toEntity(files.getFileName(), files.getFileUrl(), place));
      fileList.add(save);

      fileService.save(placeRequest.getFile().get(0));
            }
```

- 공간 등록 시 AWS S3 API이용 하여 이미지 파일을 S3에 저장
- S3에 저장된 이미지 파일의 URL을 DB에 저장
- DB에 저장된 이미지 파일의 URL을 통해 이미지 파일을 불러옴
- 불러온 이미지 파일을 Base64로 인코딩하여 앱에 전달
- 앱에서 Base64로 인코딩된 이미지 파일을 디코딩하여 이미지 파일을 불러옴

![Honeycam 2023-05-10 20-18-08](https://github.com/clean17/Village-Front-Project/assets/118657689/deb96fa9-7540-492e-acb9-5242ad903339)
- 공간 등록시 해시태그 , 편의 시설 , 파일, 요일, 카테고리 , 공간 정보를 저장하기 위해 각각의 Repository를 생성하고 Service를 생성하여 저장하는 로직을 구현
- 공간 정보를 저장하기 위해 placeJpaRepository를 생성하고 PlaceService를 생성하여 저장하는 로직을 구현

#### 공간 insert
```java
    placeRequest.setStatus(PlaceStatus.INACTIVE);
    placeRequest.setUser(user);

    Place savePlace = placeJpaRepository.save(placeRequest.toEntity());
```
#### 해시태그 insert
```java

  List<Hashtag> hashtagList = new ArrayList<Hashtag>();

  for (HashtagSaveDTO.HashtagSaveDto hash : placeRequest.getHashtag()) {
      Hashtag saveHashtag = hashtagRepository.save(hash.toEntity(hash.getHashtagName(), place));

      hashtagList.add(saveHashtag);
  }
```
#### 편의 시설 insert
```java
  List<FacilityInfo> facilityInfoList = new ArrayList<FacilityInfo>();

  for (FacilityInfoSaveDTO.FacilityInfoSaveDto facilityInfo : placeRequest.getFacilityInfo()) {
      FacilityInfo savefacilityInfo = facilityInfoRepository.save(facilityInfo.toEntity(facilityInfo.getFacilityName(), place));

      facilityInfoList.add(savefacilityInfo);
  }
```

#### 요일 날짜 insert
```java

    List<Dates> dateList = new ArrayList<Dates>();

    for (DateSaveDTO.DateSaveDto date : placeRequest.getDayOfWeek()) {
        Dates saveDate = dateRepository.save(date.toEntity(date.getDayOfWeekName(), place));

        dateList.add(saveDate);
    }
```

#### 카테고리 insert
```java
    Category category = new Category();
    category.setCategoryName(placeRequest.getCategoryName());
    category.setPlace(place);
    categoryRepository.save(category);
```
![Honeycam 2023-05-10 20-18-23](https://github.com/clean17/Village-Front-Project/assets/118657689/25bcb04b-bd8d-4952-9722-c8249744d1cc)



#### 관리자 페이지 <br>
![image](https://github.com/clean17/Village-Front-Project/assets/118657689/c61aa2e9-5022-4433-ab8a-ae9087b1fc85)

