# OutBoxPattern
A project implementing OutBox Message Pattern.

Clean Architecture Solution.
exp: Order-> Shipment
#1 场景1：
当你提交一个订单时候，订单事件触发自动生成一个出货单（shipment）。
一般情况为了事务一致性，订单和出货单要一生成，s一个

