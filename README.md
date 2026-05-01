Cài đặt Docker Desktop. <br>
Remove-Item -Recurse -Force "C:\ProgramData\DockerDesktop" <br>
winget source update <br>
winget install -e --id Docker .DockerDesktop <br>
Mở Terminal tại thư mục chứa file đó.<br>
Gõ lệnh: docker-compose up -d<br>
CREATE TABLE stores (
    id SERIAL PRIMARY KEY,
    store_name VARCHAR(255) NOT NULL,
    address TEXT,
    location GEOMETRY(Point, 4326)
);
INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 1)', 
    '24 Nguyễn Trãi, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.740399 9.988934)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 2)', 
    '90 Võ Văn Ngân, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.610454 10.982872)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 3)', 
    '140 Hoàng Văn Thụ, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.857871 10.978406)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 4)', 
    '396 Lê Lợi, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.794080 10.955586)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 5)', 
    '247 Lê Lợi, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.751545 10.021612)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 6)', 
    '473 Lê Văn Việt, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.810900 10.082365)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 3 (Chi nhánh 7)', 
    '430 Lê Văn Việt, Quận 3, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.690636 10.774236)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cầu Giấy (Chi nhánh 8)', 
    '543 Nguyễn Trãi, Cầu Giấy, Hà Nội', 
    ST_GeomFromText('POINT(105.841182 21.026688)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 9)', 
    '190 Cách Mạng Tháng 8, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.605452 10.975244)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 10)', 
    '609 Hoàng Văn Thụ, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.624459 10.956718)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 11)', 
    '516 Lê Lợi, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.816120 10.925843)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 12)', 
    '515 Võ Văn Ngân, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.825805 10.994619)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 13)', 
    '773 Quang Trung, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.750002 10.075316)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 14)', 
    '726 Quang Trung, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.819290 10.009809)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Biên Hòa (Chi nhánh 15)', 
    '288 Võ Văn Ngân, Biên Hòa, Đồng Nai', 
    ST_GeomFromText('POINT(106.802332 10.945777)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Dĩ An (Chi nhánh 16)', 
    '388 Cách Mạng Tháng 8, Dĩ An, Bình Dương', 
    ST_GeomFromText('POINT(106.658730 10.935293)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 10 (Chi nhánh 17)', 
    '517 Đường 3/2, Quận 10, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.689802 10.740287)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Dĩ An (Chi nhánh 18)', 
    '23 Cách Mạng Tháng 8, Dĩ An, Bình Dương', 
    ST_GeomFromText('POINT(106.667044 10.998305)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thanh Xuân (Chi nhánh 19)', 
    '539 Quang Trung, Thanh Xuân, Hà Nội', 
    ST_GeomFromText('POINT(105.851721 21.078413)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 20)', 
    '322 Nguyễn Thị Minh Khai, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.816782 10.002324)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 21)', 
    '443 Đường 3/2, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.818908 10.080127)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 22)', 
    '796 Hoàng Văn Thụ, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.775012 10.044619)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Biên Hòa (Chi nhánh 23)', 
    '49 Lê Văn Việt, Biên Hòa, Đồng Nai', 
    ST_GeomFromText('POINT(106.798809 10.945381)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 24)', 
    '256 Nguyễn Thị Minh Khai, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.785639 10.058256)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thủ Dầu Một (Chi nhánh 25)', 
    '517 Cách Mạng Tháng 8, Thủ Dầu Một, Bình Dương', 
    ST_GeomFromText('POINT(106.694892 10.962715)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Tân Bình (Chi nhánh 26)', 
    '146 Quang Trung, Tân Bình, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.703418 10.773592)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Hai Bà Trưng (Chi nhánh 27)', 
    '565 Quang Trung, Hai Bà Trưng, Hà Nội', 
    ST_GeomFromText('POINT(105.833778 21.048278)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ba Đình (Chi nhánh 28)', 
    '421 Cách Mạng Tháng 8, Ba Đình, Hà Nội', 
    ST_GeomFromText('POINT(105.829456 21.056034)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 29)', 
    '20 Nguyễn Thị Minh Khai, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.827912 9.988902)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thủ Đức (Chi nhánh 30)', 
    '778 Nguyễn Thị Minh Khai, Thủ Đức, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.662490 10.754271)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Hai Bà Trưng (Chi nhánh 31)', 
    '581 Nguyễn Trãi, Hai Bà Trưng, Hà Nội', 
    ST_GeomFromText('POINT(105.840342 21.069859)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cầu Giấy (Chi nhánh 32)', 
    '56 Nguyễn Thị Minh Khai, Cầu Giấy, Hà Nội', 
    ST_GeomFromText('POINT(105.860805 20.978777)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 33)', 
    '358 Lê Văn Việt, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.793521 10.026159)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 7 (Chi nhánh 34)', 
    '106 Lê Văn Việt, Quận 7, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.701121 10.793139)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Biên Hòa (Chi nhánh 35)', 
    '236 Cách Mạng Tháng 8, Biên Hòa, Đồng Nai', 
    ST_GeomFromText('POINT(106.830143 10.960697)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 36)', 
    '191 Võ Văn Ngân, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.816652 10.036963)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Bình Thạnh (Chi nhánh 37)', 
    '349 Cách Mạng Tháng 8, Bình Thạnh, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.680807 10.799279)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cầu Giấy (Chi nhánh 38)', 
    '746 Quang Trung, Cầu Giấy, Hà Nội', 
    ST_GeomFromText('POINT(105.879932 21.016500)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 39)', 
    '295 Lê Lợi, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.781866 10.001667)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 10 (Chi nhánh 40)', 
    '172 Nguyễn Trãi, Quận 10, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.694995 10.753003)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Hoàn Kiếm (Chi nhánh 41)', 
    '228 Võ Văn Ngân, Hoàn Kiếm, Hà Nội', 
    ST_GeomFromText('POINT(105.893863 21.029633)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 42)', 
    '257 Cách Mạng Tháng 8, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.640548 11.025929)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 43)', 
    '240 Trần Hưng Đạo, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.748973 10.003733)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 44)', 
    '445 Đường 3/2, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.673052 10.957557)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 45)', 
    '684 Đường 3/2, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.615500 10.936679)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thủ Dầu Một (Chi nhánh 46)', 
    '736 Nguyễn Trãi, Thủ Dầu Một, Bình Dương', 
    ST_GeomFromText('POINT(106.662113 10.971688)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Hai Bà Trưng (Chi nhánh 47)', 
    '629 Lê Lợi, Hai Bà Trưng, Hà Nội', 
    ST_GeomFromText('POINT(105.896806 21.008179)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Dĩ An (Chi nhánh 48)', 
    '190 Lê Lợi, Dĩ An, Bình Dương', 
    ST_GeomFromText('POINT(106.679828 10.954455)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thủ Đức (Chi nhánh 49)', 
    '195 Cách Mạng Tháng 8, Thủ Đức, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.711987 10.761046)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thủ Dầu Một (Chi nhánh 50)', 
    '557 Nguyễn Thị Minh Khai, Thủ Dầu Một, Bình Dương', 
    ST_GeomFromText('POINT(106.679902 11.014074)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Gò Vấp (Chi nhánh 51)', 
    '87 Cách Mạng Tháng 8, Gò Vấp, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.743626 10.801099)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Tân Bình (Chi nhánh 52)', 
    '466 Đường 3/2, Tân Bình, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.667406 10.743557)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 3 (Chi nhánh 53)', 
    '719 Hoàng Văn Thụ, Quận 3, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.699071 10.798710)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 54)', 
    '306 Nguyễn Trãi, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.773669 10.050987)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 55)', 
    '289 Quang Trung, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.644682 11.029276)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thủ Đức (Chi nhánh 56)', 
    '684 Lê Lợi, Thủ Đức, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.734221 10.812246)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 57)', 
    '187 Nguyễn Trãi, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.794357 9.988164)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cầu Giấy (Chi nhánh 58)', 
    '769 Võ Văn Ngân, Cầu Giấy, Hà Nội', 
    ST_GeomFromText('POINT(105.850865 21.022406)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thủ Dầu Một (Chi nhánh 59)', 
    '661 Võ Văn Ngân, Thủ Dầu Một, Bình Dương', 
    ST_GeomFromText('POINT(106.689128 10.940672)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 60)', 
    '755 Nguyễn Thị Minh Khai, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.756726 10.057708)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Tân Bình (Chi nhánh 61)', 
    '78 Võ Văn Ngân, Tân Bình, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.666885 10.750028)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 10 (Chi nhánh 62)', 
    '186 Nguyễn Trãi, Quận 10, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.723816 10.768803)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 63)', 
    '93 Lê Lợi, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.742510 10.073102)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Biên Hòa (Chi nhánh 64)', 
    '571 Nguyễn Thị Minh Khai, Biên Hòa, Đồng Nai', 
    ST_GeomFromText('POINT(106.864146 10.956739)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 65)', 
    '777 Cách Mạng Tháng 8, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.784673 10.030702)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cầu Giấy (Chi nhánh 66)', 
    '512 Trần Hưng Đạo, Cầu Giấy, Hà Nội', 
    ST_GeomFromText('POINT(105.861328 21.032780)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 67)', 
    '489 Cách Mạng Tháng 8, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.634294 10.997429)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 1 (Chi nhánh 68)', 
    '610 Trần Hưng Đạo, Quận 1, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.734469 10.744137)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 69)', 
    '97 Trần Hưng Đạo, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.780141 10.911257)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 70)', 
    '601 Nguyễn Thị Minh Khai, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.842523 10.945587)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Gò Vấp (Chi nhánh 71)', 
    '439 Đường 3/2, Gò Vấp, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.658983 10.746445)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Gò Vấp (Chi nhánh 72)', 
    '301 Đường 3/2, Gò Vấp, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.727628 10.744461)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 73)', 
    '380 Nguyễn Thị Minh Khai, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.686314 11.008320)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Hoàn Kiếm (Chi nhánh 74)', 
    '289 Đường 3/2, Hoàn Kiếm, Hà Nội', 
    ST_GeomFromText('POINT(105.818115 21.043650)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 3 (Chi nhánh 75)', 
    '527 Võ Văn Ngân, Quận 3, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.651216 10.813784)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 76)', 
    '234 Cách Mạng Tháng 8, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.795645 9.986585)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Gò Vấp (Chi nhánh 77)', 
    '18 Quang Trung, Gò Vấp, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.745305 10.742977)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 78)', 
    '124 Quang Trung, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.742690 10.069279)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Biên Hòa (Chi nhánh 79)', 
    '787 Lê Lợi, Biên Hòa, Đồng Nai', 
    ST_GeomFromText('POINT(106.855489 10.974562)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cầu Giấy (Chi nhánh 80)', 
    '147 Cách Mạng Tháng 8, Cầu Giấy, Hà Nội', 
    ST_GeomFromText('POINT(105.874850 21.037594)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 7 (Chi nhánh 81)', 
    '134 Quang Trung, Quận 7, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.672329 10.754307)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 82)', 
    '633 Trần Hưng Đạo, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.628724 10.989662)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 83)', 
    '462 Nguyễn Trãi, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.815783 10.979713)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 84)', 
    '481 Lê Lợi, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.691300 10.938468)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 1 (Chi nhánh 85)', 
    '698 Lê Lợi, Quận 1, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.695194 10.735830)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 86)', 
    '469 Lê Văn Việt, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.781160 10.971121)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Đống Đa (Chi nhánh 87)', 
    '109 Quang Trung, Đống Đa, Hà Nội', 
    ST_GeomFromText('POINT(105.804879 21.076418)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Dĩ An (Chi nhánh 88)', 
    '776 Võ Văn Ngân, Dĩ An, Bình Dương', 
    ST_GeomFromText('POINT(106.637331 10.937837)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thanh Xuân (Chi nhánh 89)', 
    '721 Cách Mạng Tháng 8, Thanh Xuân, Hà Nội', 
    ST_GeomFromText('POINT(105.899444 20.999482)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 90)', 
    '525 Quang Trung, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.762270 10.076788)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ba Đình (Chi nhánh 91)', 
    '466 Đường 3/2, Ba Đình, Hà Nội', 
    ST_GeomFromText('POINT(105.851777 21.060434)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cầu Giấy (Chi nhánh 92)', 
    '8 Cách Mạng Tháng 8, Cầu Giấy, Hà Nội', 
    ST_GeomFromText('POINT(105.805847 21.056761)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 93)', 
    '4 Trần Hưng Đạo, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.808641 10.062905)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Hoàn Kiếm (Chi nhánh 94)', 
    '712 Hoàng Văn Thụ, Hoàn Kiếm, Hà Nội', 
    ST_GeomFromText('POINT(105.835520 20.994265)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 95)', 
    '135 Quang Trung, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.621291 10.969805)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Dĩ An (Chi nhánh 96)', 
    '102 Cách Mạng Tháng 8, Dĩ An, Bình Dương', 
    ST_GeomFromText('POINT(106.644361 11.012674)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cầu Giấy (Chi nhánh 97)', 
    '44 Nguyễn Thị Minh Khai, Cầu Giấy, Hà Nội', 
    ST_GeomFromText('POINT(105.900708 21.031915)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 98)', 
    '261 Lê Văn Việt, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.828857 10.018673)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thủ Dầu Một (Chi nhánh 99)', 
    '649 Lê Văn Việt, Thủ Dầu Một, Bình Dương', 
    ST_GeomFromText('POINT(106.627478 11.010134)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Dĩ An (Chi nhánh 100)', 
    '326 Võ Văn Ngân, Dĩ An, Bình Dương', 
    ST_GeomFromText('POINT(106.694487 11.002336)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 101)', 
    '627 Cách Mạng Tháng 8, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.784105 10.014004)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Gò Vấp (Chi nhánh 102)', 
    '724 Trần Hưng Đạo, Gò Vấp, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.706569 10.825034)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 103)', 
    '446 Nguyễn Trãi, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.867379 10.954176)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thủ Dầu Một (Chi nhánh 104)', 
    '393 Trần Hưng Đạo, Thủ Dầu Một, Bình Dương', 
    ST_GeomFromText('POINT(106.604993 11.005885)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Đống Đa (Chi nhánh 105)', 
    '178 Quang Trung, Đống Đa, Hà Nội', 
    ST_GeomFromText('POINT(105.873978 21.053597)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thủ Dầu Một (Chi nhánh 106)', 
    '477 Nguyễn Trãi, Thủ Dầu Một, Bình Dương', 
    ST_GeomFromText('POINT(106.669633 11.009118)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 107)', 
    '20 Lê Lợi, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.836607 10.945976)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 1 (Chi nhánh 108)', 
    '503 Lê Lợi, Quận 1, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.651883 10.743009)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 109)', 
    '721 Hoàng Văn Thụ, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.855700 10.905452)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 110)', 
    '656 Lê Văn Việt, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.789334 9.991162)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thanh Xuân (Chi nhánh 111)', 
    '418 Hoàng Văn Thụ, Thanh Xuân, Hà Nội', 
    ST_GeomFromText('POINT(105.852875 20.992364)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 112)', 
    '658 Lê Văn Việt, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.620736 10.964635)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 113)', 
    '327 Nguyễn Trãi, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.813632 10.076815)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Biên Hòa (Chi nhánh 114)', 
    '393 Võ Văn Ngân, Biên Hòa, Đồng Nai', 
    ST_GeomFromText('POINT(106.857510 10.953567)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Bình Thạnh (Chi nhánh 115)', 
    '774 Nguyễn Thị Minh Khai, Bình Thạnh, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.736124 10.783731)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 116)', 
    '26 Hoàng Văn Thụ, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.784382 10.005886)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 117)', 
    '414 Cách Mạng Tháng 8, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.762013 10.054016)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 10 (Chi nhánh 118)', 
    '91 Nguyễn Thị Minh Khai, Quận 10, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.713694 10.780202)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Hai Bà Trưng (Chi nhánh 119)', 
    '234 Nguyễn Trãi, Hai Bà Trưng, Hà Nội', 
    ST_GeomFromText('POINT(105.834605 20.985712)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Biên Hòa (Chi nhánh 120)', 
    '795 Trần Hưng Đạo, Biên Hòa, Đồng Nai', 
    ST_GeomFromText('POINT(106.869956 10.919999)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 121)', 
    '4 Đường 3/2, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.816862 10.951946)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Hai Bà Trưng (Chi nhánh 122)', 
    '454 Trần Hưng Đạo, Hai Bà Trưng, Hà Nội', 
    ST_GeomFromText('POINT(105.844951 21.023011)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Dĩ An (Chi nhánh 123)', 
    '85 Cách Mạng Tháng 8, Dĩ An, Bình Dương', 
    ST_GeomFromText('POINT(106.618999 10.980293)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 124)', 
    '212 Võ Văn Ngân, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.780409 10.031048)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 7 (Chi nhánh 125)', 
    '236 Hoàng Văn Thụ, Quận 7, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.666149 10.808679)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 126)', 
    '529 Hoàng Văn Thụ, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.807772 10.923332)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 127)', 
    '22 Quang Trung, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.682467 10.974240)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Dĩ An (Chi nhánh 128)', 
    '140 Lê Lợi, Dĩ An, Bình Dương', 
    ST_GeomFromText('POINT(106.644792 11.015971)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 129)', 
    '399 Lê Lợi, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.830358 10.059691)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 130)', 
    '22 Đường 3/2, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.762128 10.036281)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 7 (Chi nhánh 131)', 
    '728 Cách Mạng Tháng 8, Quận 7, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.656592 10.768910)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Bình Thạnh (Chi nhánh 132)', 
    '108 Nguyễn Thị Minh Khai, Bình Thạnh, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.696776 10.803328)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Biên Hòa (Chi nhánh 133)', 
    '412 Hoàng Văn Thụ, Biên Hòa, Đồng Nai', 
    ST_GeomFromText('POINT(106.786470 10.983712)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Hoàn Kiếm (Chi nhánh 134)', 
    '561 Võ Văn Ngân, Hoàn Kiếm, Hà Nội', 
    ST_GeomFromText('POINT(105.902168 20.988304)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ba Đình (Chi nhánh 135)', 
    '287 Lê Lợi, Ba Đình, Hà Nội', 
    ST_GeomFromText('POINT(105.837535 21.054285)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ba Đình (Chi nhánh 136)', 
    '111 Lê Lợi, Ba Đình, Hà Nội', 
    ST_GeomFromText('POINT(105.902602 21.032824)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 137)', 
    '351 Trần Hưng Đạo, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.800971 9.984291)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Hoàn Kiếm (Chi nhánh 138)', 
    '603 Võ Văn Ngân, Hoàn Kiếm, Hà Nội', 
    ST_GeomFromText('POINT(105.895890 20.984435)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thuận An (Chi nhánh 139)', 
    '89 Trần Hưng Đạo, Thuận An, Bình Dương', 
    ST_GeomFromText('POINT(106.679402 10.975049)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cầu Giấy (Chi nhánh 140)', 
    '244 Nguyễn Thị Minh Khai, Cầu Giấy, Hà Nội', 
    ST_GeomFromText('POINT(105.831573 21.037653)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 10 (Chi nhánh 141)', 
    '594 Võ Văn Ngân, Quận 10, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.743438 10.754029)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 142)', 
    '340 Lê Văn Việt, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.805023 10.015874)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 143)', 
    '649 Cách Mạng Tháng 8, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.852489 10.918240)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Dĩ An (Chi nhánh 144)', 
    '102 Đường 3/2, Dĩ An, Bình Dương', 
    ST_GeomFromText('POINT(106.613074 11.019666)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Long Khánh (Chi nhánh 145)', 
    '48 Nguyễn Trãi, Long Khánh, Đồng Nai', 
    ST_GeomFromText('POINT(106.782719 10.925670)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thanh Xuân (Chi nhánh 146)', 
    '361 Cách Mạng Tháng 8, Thanh Xuân, Hà Nội', 
    ST_GeomFromText('POINT(105.857537 21.046204)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Thủ Đức (Chi nhánh 147)', 
    '289 Nguyễn Trãi, Thủ Đức, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.749268 10.742506)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Cái Răng (Chi nhánh 148)', 
    '578 Đường 3/2, Cái Răng, Cần Thơ', 
    ST_GeomFromText('POINT(105.733982 10.038519)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Quận 7 (Chi nhánh 149)', 
    '505 Cách Mạng Tháng 8, Quận 7, TP. Hồ Chí Minh', 
    ST_GeomFromText('POINT(106.744535 10.795624)', 4326)
);

INSERT INTO stores (store_name, address, location)
VALUES (
    'CellphoneS - Ninh Kiều (Chi nhánh 150)', 
    '117 Lê Văn Việt, Ninh Kiều, Cần Thơ', 
    ST_GeomFromText('POINT(105.762341 10.050887)', 4326)
);
