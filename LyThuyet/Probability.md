# Ex1: A box contains three marbles — one red, one green, and one blue. Consider an experiment that consists of taking one marble from the box, then replacing it in the box and drawing a second marble from the box. Describe the sample space.
## Dịch sang tiếng Việt
Một hộp chứa ba viên bi — một viên đỏ, một viên xanh lá cây và một viên xanh dương. Xem xét một thí nghiệm bao gồm việc lấy một viên bi từ hộp, sau đó đặt nó trở lại hộp và rút viên bi thứ hai từ hộp. Mô tả không gian mẫu.
## Giải
- Lần đầu tiên, ta có thể rút một trong ba viên bi: Đỏ (R), Xanh lá cây (G), hoặc Xanh dương (B). Là tổ hợp {R, G, B} = 3.
- Sau khi rút viên bi đầu tiên, ta đặt nó trở lại hộp. Do đó, lần thứ hai ta vẫn có thể rút một trong ba viên bi. Là tổ hợp {R, G, B} = 3.
- Tổng = tích của số kết quả của lần rút đầu tiên và số kết quả của lần rút thứ hai: 3 * 3 = 9.
- Không gian mẫu (S) bao gồm tất cả các tổ hợp có thể xảy ra khi rút hai viên bi:
  S = { (R, R), (R, G), (R, B), (G, R), (G, G), (G, B), (B, R), (B, G), (B, B) }

# Ex2: An experiment consists of tossing a coin three times. What is the sample space of this experiment? Which event corresponds to the experiment resulting in more heads than tails?
## Dịch sang tiếng Việt
Một thí nghiệm bao gồm việc tung một đồng xu ba lần. Không gian mẫu của thí nghiệm này là gì? Sự kiện nào tương ứng với việc thí nghiệm có nhiều mặt ngửa hơn mặt sấp?
## Giải
- Không gian mẫu (S) của thí nghiệm này bao gồm tất cả các kết quả có thể xảy ra khi tung đồng xu ba lần:
  S = { (H, H, H), (H, H, T), (H, T, H), (H, T, T), (T, H, H), (T, H, T), (T, T, H), (T, T, T) }
- Trong đó H đại diện cho mặt ngửa và T đại diện cho mặt sấp.
- Sự kiện có nhiều mặt ngửa hơn mặt sấp có thể được mô tả như sau:
  E = { (H, H, H), (H, H, T), (H, T, H), (T, H, H) }
- Vậy sự kiện E bao gồm các kết quả có ít nhất hai mặt ngửa.

# Ex3: Let S = { 1, 2, 3, 4, 5, 6, 7 } , E = { 1, 3, 5, 7 } , F = { 7, 4, 6 } , G = { 1, 4 } . Find (a) EF ; (c) EG c ; (e) E c ( F ∪ G ) ; (b) E ∪ FG ; (d) EF c ∪ G ; (f ) EG ∪ FG
## Câu a
- EF = E ∩ F = { 1, 3, 5, 7 } ∩ { 7, 4, 6 } = { 7 }
## Câu b
- E ∪ FG = E ∪ (F ∩ G) = { 1, 3, 5, 7 } ∪ ({ 7, 4, 6 } ∩ { 1, 4 }) = { 1, 3, 5, 7 } ∪ { 4 } = { 1, 3, 4, 5, 7 }
## Câu c
- EG c = E ∩ G c = { 1, 3, 5, 7 } ∩ { 2, 3, 5, 6, 7 } = { 3, 5, 7 }
## Câu d
- EF c ∪ G = (E ∩ F c) ∪ G = ({ 1, 3, 5, 7 } ∩ { 1, 2, 3, 5 }) ∪ { 1, 4 } = { 1, 3, 5 } ∪ { 1, 4 } = { 1, 3, 4, 5 }
## Câu e
- E c ( F ∪ G ) = { 2, 4, 6 } ∩ ({ 7, 4, 6 } ∪ { 1, 4 }) = { 2, 4, 6 } ∩ { 1, 4, 6, 7 } = { 4, 6 }
## Câu f
- EG ∪ FG = (E ∩ G) ∪ (F ∩ G) = ({ 1, 3, 5, 7 } ∩ { 1, 4 }) ∪ ({ 7, 4, 6 } ∩ { 1, 4 }) = { 1 } ∪ { } = { 1 }