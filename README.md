Setup để tạo class C++ (quan trọng)
1. Đầu tiên, mình sẽ tạo class C++ để test, đảm bảo project được setup đúng cách.

Ở hàng trên cùng, vào Tools -> New C++ Class


2. Ở phần "Common Classes" -> chọn "None" -> sau đó nhấn "Next".


3. Đặt tên class là "MyClassTest" để test, sau đó nhấn "Create Class", cẩn thận làm theo những bước tiếp theo.



4. Lần đầu tạo class C++ cho project, những ô thông báo này sẽ hiện lên.

Bước này nhấn "OK".


5. Nhấn "Yes".

Visual Studio 2022 đã bật lên. Đảm bảo đã cài đặt Visual Studio 2022.


6. Project đã có class C++ mới, để project Unreal nhận class C++ mới, bạn phải vào Visual Studio và compile.

Trước khi compile bên Visual Studio, tắt Unreal Editor.

7. Khi tạo class C++ mới, trong phần  "Solution Explorer" sẽ hiển thị 2 file .cpp và .h của class đó.

Đảm bảo trong Games/Source/FirstProject/ có chứa class C++ mới tạo.


8. LẦN ĐẦU TIÊN tạo class C++, bạn phải chọn project để compile.

Vào "Games" -> click chuột phải vào "FirstProject" -> chọn "Set as Startup Project".


9. Nhấn nút Compile.

Một lần nữa, trước khi compile trong Visual Studio, đảm bảo đã tắt Unreal Editor.


10. Trong mục "Output" ở dưới, kết quả là "succeeded" nghĩa là đã compile thành công.

Khi compile thành công, Unreal Editor tự động mở lên. Vì vậy bạn không cần phải mở file .uproject nữa.

Mình sẽ không tắt Visual Studio, giữ lại cửa sổ Visual Studio cho những bước tiếp theo.


11. Khi đã làm xong những bước trên, bây giờ mình sẽ tạo 1 class C++ cho bài học sau, để đảm bảo bài giảng sau thuận lợi.

Tools -> New C++ Class...


12. Vào mục "All Classes" -> tìm và chọn "AIController" -> sau đó nhấn "Next".


13. Đặt tên class "AIController" mới là "TeamAIController" -> nhấn "Create Class".

Ở bài giảng sau, mình sẽ giải thích tại sao phải tạo class "AIController" mới.



14. Qua bên Visual Studio -> đợi và nhấn "Reload All".

Khi tạo class C++ trong lúc Visual Studio đang mở, Visual sẽ nhắc mình "Reload All" để cập nhật, và hiển thị class mới bên Visual.


15. Sau khi "Reload All", trong mục "Solution Explorer" bạn sẽ thấy class mới.

Nếu ở bước trước, bạn không nhấn "Reload All", thì có thể bạn sẽ không thấy class mới. Nếu vậy, bạn phải tắt Visual Studio -> vào folder project -> mở file .sln lên để Visual Studio cập nhật thay đổi.


16. Nhấn compile để Unreal Editor cập nhật class C++ mới.


17. Sau khi compile thành công, và Unreal Editor đã mở lên. Mình sẽ hiển thị các class C++.

Ở mục Content Drawer -> vào Settings -> chọn "Show C++ Classes".


18. Folder "C++ Classes" đã có, vào folder "FirstProject" và đảm bảo đã có class "TeamAIController".

Và bạn đã tạo xong class C++.
