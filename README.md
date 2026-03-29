This code example uses pretrained models for image recognition.

usage:

`java -jar target/imgrecognition-0.0.1-SNAPSHOT.jar`


##Practice exercise
Create a new image dataset based on the ideas given below.
Electronics
Product Ideas: Smartphones, Laptops, Tablets, Headphones, Cameras, Televisions.
Image Sources:
Unsplash (creativecommons): https://unsplash.com/s/photos/electronics
Pexels: https://www.pexels.com/search/electronics/
Amazon Product Images: You can scrape images from Amazon listings using their Product Advertising API (be mindful of usage terms and conditions).
Fashion & Apparel
Product Ideas: Shoes, Bags, Dresses, Jeans, Jackets, T-shirts.
Image Sources:
Fashion istock: https://istockphoto.com/collections/fashion
Amazon, Zalando, etc.: Similar to electronics, product images can be scraped but ensure compliance with the terms.
Food
Product Ideas: Various types of fruits, vegetables, packaged food, beverages.
Image Sources:
Unsplash (creativecommons): https://unsplash.com/s/photos/food Pexels: https://www.pexels.com/search/food/
Home Decor
Product Ideas: Furniture, Rugs, Lighting, Wall Art, Kitchen Appliances.
Image Sources:
Pexels: https://www.pexels.com/search/home%20decor/
Unsplash (creativecommons): https://unsplash.com/s/photos/home-decor
Amazon Product Images: If utilized, ensure proper citation or use a commercial license.
Automotive
Product Ideas: Cars, Motorcycles, Bicycles.
Image Sources:
Pexels: https://www.pexels.com/search/automotive/
Unsplash (creativecommons): https://unsplash.com/s/photos/automotive
Car and Driver images: https://www.caranddriver.com/photos/ (some images are available for purchasing for commercial use).
General Guidelines:
Licensing: Always ensure the images you use are properly licensed for your intended use (commercial/non-commercial). Creativity-commons licenses on platforms like Unsplash and Pexels are generally safe for most purposes but verify the specific terms.
Diversity:: Aim for a diverse set of images - different angles, lighting conditions, product variations (colors, models, etc.).
Data Augmentation: To enhance your dataset without needing more images, consider using data augmentation techniques to generate variations of existing images.
When downloading and using these images, remember to respect copyright and terms of service of each platform. This will help you avoid legal issues while building a robust dataset.
Modify the code of the image recognition application to train with the new images and perform image recognition. Hint - Change the String imagePath to the new image file.