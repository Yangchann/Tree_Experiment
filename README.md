<h1><b>:memo:Thực nghiệm đo chiều cao cây AVL và cây Đỏ - đen</b></h1>
<h2>:large_blue_diamond:Mô tả</h2>
Reposity Tree_Experiment chứa toàn bộ dữ liệu và mã nguồn để tạo ra AVL Tree, RedBlack Tree và đo chiều cao của chúng thông qua 10 bộ dữ liệu được ra ngẫu
nhiên (mỗi bộ dữ liệu chứa khoảng 10^6 giá trị).
<h2>:large_blue_diamond:Cấu trúc Repository</h2> 

Repository chứa 3 folder để tiến hành thực nghiệm và 1 file báo báo:

- GenerateTest:
  +  "GenerateTest.cpp": code C++ để tạo ra 10 bộ dữ liệu ngẫu nhiên "Test1.txt", "Test2.txt",… "Test10" (mỗi bộ dữ liệu chứa khoảng 10^6 giá trị)  
  + "logN_145logN.txt": gồm 10 dòng, mỗi dòng chứa 2 giá trị logN và 1.45logN (với N là số giá trị trong mỗi bộ dữ liệu)
- AVLTree :
	+ "AVLTree.cpp": code C++ để tạo ra 10 cây AVL và tính chiều cao của chúng thông qua 10 bộ dữ liệu được khởi tạo trước đó.
	+ "AVLTreeHeight.txt": gồm 10 dòng chứa chiều cao của mỗi cây AVL tương ứng với 10 bộ dữ liệu.
- RedBlackTree:
	+ "RedBlackTree.cpp": code C++ để tạo ra 10 cây Đỏ - đen và tính chiều cao của chúng thông qua 10 bộ dữ liệu được khỏi tạo trước đó.
	+ "RedBlackTreeHeight.txt": gồm 10 dòng chứa chiều cao của mỗi cây Đỏ - đen tương ứng với 10 bộ dữ liệu.
- File báo cáo "BÁO_CÁO_THỰC_NGHIỆM_ĐO_CHIỀU_CAO_CÂY_NHỊ_PHÂN"

<h2>:large_blue_diamond:Quy trình thực hiện:</h2>

1. Chạy code  "GenerateTest/GenerateTest.cpp" để tạo ra 10 bộ dữ liệu ngẫu nhiên "Test1.txt", "Test2.txt",.."Test10" và file "logN_145logN.txt".
2. Chạy code "AVLTree/AVLTree.cpp" để tạo ra 10 cây AVL với 10 bộ dữ liệu khởi tạo trước đó và ghi nhận chiều cao vào file "AVLTree/AVLTreeHeight.txt"
3. Chạy code "RedBlackTree/RedBlackTree.cpp" để tạo ra 10 cây Đỏ-đen với 10 bộ dữ liệu khởi tạo trước đó và ghi nhận chiều cao vào file "RedBlackTree/RedBlackTreeHeight.txt".
4. Thu thập dữ liệu, vẽ biểu đổ và so sánh, phân tích.
5. Viết báo cáo.
