    # 💾 CHUYÊN ĐỀ TIN HỌC

## ✨ Làm quen với Visual Studio Code & Github

---

## 💡 A. TỔNG QUAN

* **VS Code:** là trình soạn thảo mã nguồn miễn phí do Microsoft phát triển, hỗ trợ rất nhiều ngôn ngữ lập trình như C++, Python, Java, JavaScript…; sở hữu hệ thống extension phong phú.
* **GitHub:** là nền tảng lưu trữ và chia sẻ mã nguồn trực tuyến, dựa trên Git. Nó cho phép quản lý phiên bản, làm việc nhóm, và tham gia vào các dự án mã nguồn mở.
* **Git:** Git là hệ thống quản lý phiên bản (**Version Control System**) giúp theo dõi lịch sử thay đổi mã nguồn, tạo nhánh, hợp nhất và làm việc nhóm hiệu quả, do Linus Torvalds tạo ra.
* **GitHub Desktop:** GitHub Desktop là ứng dụng giao diện (**GUI**) giúp bạn sử dụng Git và GitHub dễ dàng hơn mà không cần dùng lệnh.

---

## 🛠️ B. CÀI ĐẶT & THIẾT LẬP

### ⬇️ I. CÀI ĐẶT

#### 1. VS Code

1. Truy cập trang chính thức: [https://code.visualstudio.com](https://code.visualstudio.com).
2. Chọn nút **Download** phù hợp với hệ điều hành (Windows, macOS, Linux).
3. Mở file cài đặt → nhấn **Next** liên tục → chọn **Install**.
4. Sau khi cài xong, mở VSCode để kiểm tra.
5. **(Khuyến nghị)** Cài thêm extension:
    * **🌟 GitLens:** Xem lịch sử commit, tác giả từng dòng.
    * **🎨 Prettier:** Định dạng mã nguồn tự động.
    * **🔗 GitHub Pull Requests & Issues:** Quản lý PR trực tiếp trong VS Code.

> **⚠️ Lưu ý:** Chỉnh cấu hình cơ bản (Theme, font, Tiếng Việt,.. nếu cần).

#### 2. Git

1. Vào trang chính thức: [https://git-scm.com/downloads](https://git-scm.com/downloads).
2. Chọn phiên bản phù hợp với hệ điều hành (Windows/macOS/Linux).
3. Mở file cài đặt → nhấn **Next** liên tục → **Install** → **Finish**.
4. Kiểm tra bằng cách mở **Terminal/Command Prompt** và gõ: `git --version`.
5. Nếu hiện số phiên bản là cài thành công.
6. Cấu hình thông tin lần đầu:
    * `git config --global user.name "Tên của bạn"`
    * `git config --global user.email "Email của bạn"`

> **⚠️ Lưu ý:** Các cấu hình thông tin sẽ gắn liền với các commit.

#### 3. GitHub Desktop

1. Truy cập [https://desktop.github.com](https://desktop.github.com).
2. Tải về và cài đặt như phần mềm bình thường.
3. Đăng nhập bằng tài khoản GitHub.

> **⚠️ Lưu ý:**
> * Giao diện chính có các nút: **Clone a repository, Create a new repository, Add an existing repository**.
> * Có thể mở dự án bằng VSCode trực tiếp từ GitHub Desktop.

### ⚙️ II. THIẾT LẬP

#### 1. Tạo tài khoản GitHub

1. Vào [https://github.com](https://github.com).
2. Nhấn **Sign up** → nhập email, mật khẩu, username.
3. Xác nhận email để hoàn tất.

> **⚠️ Lưu ý:**
> * Sau khi đăng nhập, bạn có thể tạo repo mới bằng nút **New repository** (Tạo kho chứa mã nguồn mới).
> * Chỉnh **Public & Private**:
>     * **Public:** Ai cũng xem được.
>     * **Private:** Chỉ bạn (hoặc nhóm được cấp quyền) xem được.

#### 2. Kết nối VS Code với GitHub

1. Mở VSCode → nhấn **Ctrl + Shift + P**.
2. Gõ: **GitHub: Sign in** → chọn đăng nhập bằng trình duyệt.
3. Đăng nhập tài khoản GitHub → cấp quyền truy cập.
4. VSCode sẽ lưu token xác thực → có thể **push/pull** trực tiếp.
5. Kiểm tra tab **Source Control** đã hoạt động.

> **⚠️ Lưu ý:** Tab **Source Control** là nơi hiển thị mọi thay đổi.

#### 3. Đăng nhập tài khoản GitHub trên GitHub desktop

1. Mở GitHub Desktop.
2. Nhấn **File** → **Options** (hoặc biểu tượng bánh răng).
3. Chọn **Sign in to GitHub.com**.
4. Đăng nhập tài khoản → xác nhận.
5. Sau khi đăng nhập, có thể **clone, tạo repo, commit, push** dễ dàng.

---

## 💻 C. LÀM VIỆC CÙNG GITHUB

### I. QUA VS CODE & GITHUB DESKTOP

#### 1. Lấy dự án từ GitHub về để chỉnh sửa

##### a. Trực tiếp bằng VS Code

1. Vào GitHub → chọn repo cần lấy.
2. Nhấn nút **Code** → copy link **HTTPS**.
3. Mở VSCode → **Terminal** → gõ: `git clone <link_repo>`.
4. Mở thư mục vừa **clone** → chỉnh sửa, **commit, push**.

##### b. Thông qua GitHub Destop

1. Mở GitHub Desktop → chọn **Clone a repository** → chọn **URL**.
2. Dán link repo hoặc chọn repo từ danh sách.
3. Nhấn **Clone** → mở bằng VSCode để chỉnh sửa.

#### 2. Đưa dự án của bản thân lên GitHub

##### a. Trực tiếp bằng VS Code

1. Mở thư mục dự án bằng VSCode.
2. Mở tab **Source Control** → nhấn **Initialize Repository**.
3. Gõ nội dung **commit** → nhấn **Commit**.
4. Nhấn **Publish to GitHub** → đăng nhập tài khoản.
5. Chọn tạo repo mới hoặc repo có sẵn.
> Sau đó: Commit → Push mỗi khi cập nhật.

##### b. Thông qua GitHub Desktop

1. Mở GitHub Desktop → chọn **Create a new repository**.
2. Chọn thư mục dự án → đặt tên repo.
3. Nhấn **Publish repository** để đưa lên GitHub.
4. Sau khi chỉnh sửa → **Commit** → **Push origin**.
5. Mở bằng VSCode để tiếp tục làm việc.

### 🌐 II. TRỰC TIẾP TRÊN GITHUB QUA GITHUB CODESPACE

#### 1. GitHub CodeSpace là gì?

* Là môi trường lập trình trực tuyến giống **Visual Studio Code**.
* Chạy trực tiếp trên GitHub, không cần cài đặt phần mềm.
* Tự động tải mã nguồn, cài thư viện, và lưu thay đổi.
* Phù hợp để chỉnh sửa nhanh, làm việc nhóm, hoặc tham gia vào các dự án mã nguồn mở.

#### 2. Cách sử dụng GitHub CodeSpace

1. Vào trang GitHub → đăng nhập tài khoản.
2. Tìm địa chỉ repo bạn muốn chỉnh sửa (có thể là repo của người khác hoặc repo của bạn).
3. Nhấn nút **Code** → chọn tab **Codespaces**.
4. Nhấn **Create with Codespaces** hoặc **New codespace**.
5. GitHub sẽ mở giao diện VSCode trực tiếp trong trình duyệt.
6. Bạn có thể chỉnh sửa, commit, push ngay trên web mà không cần tải về.
7. Nếu muốn đóng góp vào dự án người khác → tạo **Pull Request**.

---

## 🤝 D. THAM GIA DỰ ÁN MÃ NGUỒN MỞ

### I. MÃ NGUỒN MỞ LÀ GÌ?

* Là các dự án phần mềm có mã nguồn công khai, ai cũng có thể xem, sử dụng, chỉnh sửa và đóng góp.
* Giúp cộng đồng cùng phát triển phần mềm, học hỏi lẫn nhau.
* Các giấy phép phổ biến: **MIT, GPL, Apache**.

### II. CÁCH THAM GIA VÀO DỰ ÁN MÃ NGUỒN MỞ

#### 1. Tìm dự án phù hợp

* Truy cập [https://github.com/explore](https://github.com/explore) hoặc [https://opensource.guide](https://opensource.guide).
* Tìm dự án theo ngôn ngữ bạn biết (Python, JavaScript, C++, v.v.).
* Ưu tiên chọn dự án có nhãn **good first issue** hoặc **help wanted**.

#### 2. Quy trình tham gia

1. **Fork** dự án: tạo bản sao repo về tài khoản của bạn.
2. **Clone** repo fork về máy để chỉnh sửa: `git clone <link_repo_fork>`.
3. Tạo nhánh mới để làm việc riêng: `git checkout -b ten-nhanh-moi`.
4. Chỉnh sửa mã nguồn → **commit** → **push** lên repo fork.
5. Tạo **Pull Request** để gửi thay đổi cho repo gốc.
6. Chủ dự án sẽ **review** → nếu đồng ý sẽ **merge** vào dự án chính.

#### 3. Lưu ý khi đóng góp

* Bạn có thể thực hiện tương tự thông qua **Github CodeSpace**.
* Đọc kỹ file **README.md** và **CONTRIBUTING.md** của dự án.
* Viết **commit** rõ ràng, dễ hiểu.
* Tôn trọng quy tắc cộng đồng, phản hồi lịch sự.
* Có thể bắt đầu bằng việc sửa lỗi nhỏ, cải thiện tài liệu, hoặc thêm tính năng đơn giản.

---

## ✅ E. TỔNG KẾT

* **VS Code:** Công cụ viết code mạnh mẽ và phổ biến.
* **Git:** Công cụ quản lý phiên bản không thể thiếu.
* **GitHub:** Nơi lưu trữ, chia sẻ mã nguồn và làm việc nhóm.
* **GitHub Desktop:** Dễ dùng, trực quan cho người mới.

> **→ Bộ công cụ giúp học sinh – sinh viên làm việc khoa học, chuyên nghiệp, hiệu quả hơn.**

---

## 📝 F. TÌM HIỂU VỀ MARKDOWN

### I. FILE MARKDOWN LÀ GÌ

* **Markdown (.md)** là một định dạng văn bản thuần (**plain text**) dùng để trình bày nội dung bằng các ký hiệu rất đơn giản.
* Bạn có thể hiểu Markdown là: “Giống Word nhưng nhẹ hơn, không dùng định dạng phức tạp, chỉ dùng ký hiệu như **#, \*, -** … để trình bày.”
* Markdown dùng cực nhiều trong:
    * GitHub (**README.md**).
    * Viết tài liệu, note.
    * VSCode.
    * Viết blog, wiki.
* Markdown không phải là file Word, nó chỉ là text + ký hiệu.

### II. CẤU TRÚC CỦA FILE MARKDOWN

| Yếu tố định dạng | Ký hiệu Markdown | Ví dụ |
| :--- | :--- | :--- |
| **Tiêu đề** | `#` (từ 1 đến 6 dấu) | `# Tiêu đề 1` |
| **In đậm** | `**...**` hoặc `__...__` | `**văn bản in đậm**` |
| **In nghiêng** | `*...*` hoặc `_..._` | `*văn bản in nghiêng*` |
| **Danh sách không thứ tự** | `*`, `+`, hoặc `-` | `* Mục 1` |
| **Danh sách có thứ tự** | Số theo sau là dấu chấm | `1. Mục đầu tiên` |
| **Khối trích dẫn** | `>` | `> Đây là trích dẫn` |
| **Liên kết** | `[Văn bản liên kết](URL)` | `[Google](https://www.google.com)` |
| **Hình ảnh** | `![Văn bản thay thế](URL hình ảnh)` | `![Ảnh ví dụ](url/anh.png)` |
| **Code Inline** | `` `...` `` | `` `print("Hello")` `` |
| **Khối code** | ``` ``` ``` (3 dấu) | `` ```python\nprint("Hello")\n``` `` |

### III. CÁCH CHUYỂN TỪ FILE WORD (.DOCX) THÀNH FILE MARKDOWN (.MD)

Có nhiều cách để chuyển từ file Word (.docx) sang file Markdown (.md):

* **Sử dụng Công cụ Chuyển đổi Trực tuyến:** Có nhiều trang web cung cấp dịch vụ chuyển đổi từ Word sang Markdown (ví dụ: Word to Markdown Converter). Bạn tải file Word lên và tải file Markdown về.
* **Sử dụng pandoc (Nâng cao):** Đây là một công cụ chuyển đổi tài liệu mạnh mẽ, thường được dùng qua Command Line (Dòng lệnh).
    * *Lệnh ví dụ:* `pandoc -s ten_file_word.docx -o ten_file_markdown.md`
* **Sử dụng các Tính năng Xuất/Lưu:** Một số phần mềm soạn thảo văn bản hoặc các plugin chuyên biệt có thể có tùy chọn **Lưu dưới dạng** (Save As) hoặc **Xuất** (Export) sang định dạng .md.
* **Sao chép và Dán:** Đối với văn bản đơn giản, bạn có thể sao chép nội dung từ Word và dán vào một trình soạn thảo Markdown, sau đó tự định dạng lại bằng tay.
* **Đưa file cho một A.I bất kì:** Yêu cầu chuyển thành file Markdown, như Genimi, ChatGPT, Copilot,…

### IV. SỬ DỤNG FILE MARKDOWN TRONG VS CODE & GITHUB

#### 1. Soạn thảo: Viết tài liệu trong VS Code

* Bạn sử dụng VS Code để viết nội dung như bình thường, nhưng thay vì dùng các nút định dạng phức tạp như trong Word, bạn sử dụng **cú pháp Markdown**.
* **Thao tác:** Mở một file mới và đặt tên là `README.md` (hoặc bất kỳ tên `.md` nào khác).
* **Điểm đặc biệt của VS Code:**
    * Cung cấp tính năng **Tô sáng cú pháp** (**Syntax Highlighting**): Nó sẽ tô màu các ký hiệu Markdown (như #, \*\*, \*) giúp bạn dễ nhận biết cú pháp hơn.
    * **Xem trước (Preview) Trực tiếp:** Đây là phần quan trọng nhất. Bạn có thể nhấn vào nút "Mở + + Xem trước" (thường là biểu tượng kính lúp hoặc tab bên cạnh) để chia màn hình làm đôi:
        * **Bên trái:** Nơi bạn gõ cú pháp Markdown (# Tiêu đề).
        * **Bên phải:** Nơi bạn thấy kết quả hiển thị như trên GitHub (một dòng chữ to và đậm).
* **Trực quan:** VS Code cho bạn thấy ngay lập tức tài liệu sẽ trông như thế nào trước khi bạn đưa nó lên mạng.

#### 2. Đưa lên GitHub: Kết nối và Đồng bộ

* Sau khi bạn đã hoàn tất việc viết tài liệu trong VS Code, bạn cần đưa nó lên **Repository** (Kho lưu trữ) trên GitHub của mình.
* **Công cụ:** Bạn sử dụng các công cụ **Quản lý phiên bản (Source Control)** tích hợp sẵn trong VS Code (thường là Git/GitHub).
* **Hành động:** Bạn **Commit** (ghi nhận các thay đổi) và sau đó **Push** (đẩy) file .md này từ máy tính của bạn lên GitHub.

#### 3. Hiển thị: Kết quả trên GitHub

* Khi file `.md` đã có mặt trên GitHub, GitHub sẽ tự động nhận diện và chuyển đổi nó.
    * **Bạn gửi:** Một file văn bản thuần túy với các ký hiệu đặc biệt.
    * **GitHub nhận:** File đó và sử dụng trình **kết xuất Markdown (Markdown Renderer)** của riêng nó.
* **Kết quả:**
    * Nếu đó là file `README.md` nằm ở thư mục gốc, nội dung sẽ hiển thị ngay trên trang chính của Repository, biến nó thành một trang giới thiệu dự án đẹp mắt.
    * Nếu đó là file tài liệu khác, khi người dùng click vào file, GitHub sẽ hiển thị nó dưới dạng trang web có định dạng hoàn chỉnh.
* **Trực quan:** File Markdown là nguyên liệu thô (cú pháp), và GitHub là cái máy in ấn (kết xuất) biến nguyên liệu thô đó thành một trang tài liệu đẹp mắt, dễ đọc trên web. Cả quá trình này được kiểm soát bởi VS Code trên máy tính của bạn.