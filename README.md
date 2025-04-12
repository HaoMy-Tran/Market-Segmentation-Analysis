# Mapping the Tourism market: A Segmentation Analysis (EN/VI)

<b>💠 English:</b><br>
I would like to thank ChatGPT – the AI assistant who supported me throughout the development of this project – as well as to Sara Dolnicar, Bettina Grün, and Friedrich Leisch for the valuable insights they’ve shared in their book “Market Segmentation Analysis: Understanding It, Doing It, and Making It Useful” as a critical instrumentals for me to complete this project.<br>

Through this project, I’ve come to realize that data analysis is fundamentally an exploratory process. Data doesn’t just answer questions; sometimes, it reshapes them.
In many cases, it is not feasible to start with a specific hypothesis. Instead, we begin with a general goal and let the data guide the way. We don’t always know what we’re looking for at the outset. And often, the data offers unexpected or even contradictory suggestions.

In this project, my initial goal was to conduct market segmentation, but I did not commit to any specific algorithm from the start. Experimenting with models such as standard K-Modes clustering and Bagged K-Modes revealed certain limitations, both in terms of output quality and the ability to reflect real customer behavior. These underperforming models provided a valuable signal: the data did not cluster according to the intended segmentation dimension (benefits and needs), but rather according to response behavior (e.g., rating all factors high or low). This unexpected result led me to explore a more suitable method.
After further research and experimentation, the “Neutral Gas” model emerged as a more flexible approach, one that better captured segmentation along the intended analytical dimensions.

This experience highlighted an important lesson: rather than focusing solely on choosing the right tools, it is the continuous testing, adjusting, and responding to what the data reveals that ultimately defines successful data analysis.


<b>💠 Vietnamese:</b><br>
<i>Tôi xin gửi lời cảm ơn đến ChatGPT – trợ lý AI đã hỗ trợ tôi trong suốt quá trình thực hiện dự án này, cũng như đến Sara Dolnicar, Bettina Grün và Friedrich Leisch và những của insight quý giá được chia sẻ trong quyển sách “Market Segmentation Analysis: Understanding It, Doing It, and Making It Useful” đã trở thành nguồn tài liệu tham khảo quan trọng giúp tôi hoàn thiện dự án này.</i>
<br>
<br><i>Sau dự án này, tôi hiểu ra rằng Phân tích dữ liệu là một quá trình mang tính khám phá, bởi vì dữ liệu không chỉ trả lời câu hỏi, đôi khi chính nó lại định hình câu hỏi. 
Trong nhiều trường hợp, đôi khi không thể đi từ một giả thuyết cụ thể mà bắt đầu từ một mục tiêu chung, rồi để dữ liệu dẫn đường.  Không phải lúc nào chúng ta cũng biết mình đang tìm gì ngay từ đầu. Dữ liệu đôi khi đưa ra những gợi ý bất ngờ, thậm chí trái với kỳ vọng.

Trong dự án này, mục tiêu ban đầu của tôi là thực hiện phân khúc thị trường, nhưng không định sẵn thuật toán nào sẽ được sử dụng. Quá trình thử nghiệm với các mô hình như standard K-Modes clustering và Bagged K-Modes cho thấy những giới hạn nhất định, cả về mặt kết quả lẫn khả năng phản ánh hành vi thực tế. Chính những mô hình chưa hiệu quả đã cung cấp tín hiệu quan trọng: dữ liệu không phân cụm theo phương diện mục tiêu đã được chọn ra làm mục tiêu phân tích (lợi ích, nhu cầu) mà phân cụm theo hành vi trả lời bảng câu hỏi (trả lời tất cả các yếu tố trên và dưới trung bình). Kết quả không như kỳ vọng này đã giúp tôi tìm đến một phương án khác phù hợp hơn. Thông qua quá trình tìm hiểu và thử nghiệm, mô hình “Neutral Gas” được xây dựng như một cách tiếp cận linh hoạt hơn, giúp nắm bắt những phân khúc thể hiện đúng phương diện của phân tích.

Trải nghiệm này cho thấy: thay vì chỉ tập trung vào lựa chọn công cụ, việc liên tục kiểm định, điều chỉnh mô hình và phản hồi lại từ chính dữ liệu mới là yếu tố quyết định trong việc Phân tích Dữ liệu.

