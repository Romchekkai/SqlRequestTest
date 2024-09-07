# SqlRequestTest
## Write sql request  to find result table as product-category:
select prod.name, category.name <br>
from prod left join category<br>
on product.category_id = catagory.ID
