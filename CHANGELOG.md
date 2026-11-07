# Changelog


Định dạng dựa trên [Keep a Changelog].

## [Unreleased]

## [1.1.0] - 2026-11-07
### Added
- `Cart.sort_by_title()` và `Cart.sort_by_cost()`.
- `search_by_category()` để tìm DVD theo thể loại.
### Fixed
- `search_by_title()` không phân biệt hoa thường (#20).

## [1.0.1] - 2026-11-07
### Fixed
- `search_by_title()` không phân biệt hoa thường (#20).

## [1.0.0] - 2026-11-07
### Added
- `Cart.print_cart()` và thông báo riêng khi giỏ rỗng.
- `search_by_title()` để tìm DVD theo tiêu đề.

### Fixed
- Giới hạn giỏ hàng: từ chối DVD thứ 21 (#7).
- Sửa công thức tính giảm giá và kiểm tra điều kiện phần trăm trong `total_cost_with_discount()`

