# Shopify Featured Products Section

## Github репозиторій
https://github.com/PetroFx7/Shopify
## Інструкція по збірці та роботі з проектом

### 1. Клонування репозиторію
git clone https://github.com/yourusername/shopify-featured-products.git
cd shopify-featured-products

### 2. Підготовка dev environment
Використовуйте Shopify CLI або Theme Editor:
shopify login --store your-test-store.myshopify.com
shopify theme dev
Або редагуйте тему безпосередньо через Shopify Admin → Online Store → Themes → Actions → Edit code.

### 3. Додавання секції
Секція додана у папку sections/featured-products.liquid. Для використання у шаблоні:
{% section 'featured-products' %}

### 4. Тестування
При завантаженні сторінки товари, що вже в кошику, не відображаються. Натискання кнопки Add to cart додає товар у кошик без перезавантаження сторінки, видаляє товар з секції Featured Products та оновлює header cart count і суму кошика динамічно.

## Тестовий Shopify магазин
Посилання: https://qab00j-xy.myshopify.com/ 
Пароль: yahrte
