# SqlRequestTest
Write sql request  to find result table as product-category:
select prod.name, category.name 
from prod left join category
on product.category_id = catagory.ID
