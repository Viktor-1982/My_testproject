# My_testproject
conftest.py     # инициализация браузера на нужном языке

base_page.py    # импорт браузера из conftest.py + общие методы, применимые к любой странице

main_page.py    # импорт всего из base_page + методы, применимые на main page

test_main_page.py   # импорт всего из main_page + конкретные тесткейсы и url, и методы, необходимые в тесткейсе вызываются из base_page и main_page по мере надобности.
