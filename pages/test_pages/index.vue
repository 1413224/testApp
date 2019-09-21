<template>
	<view class="test_box">
		<view class="card">
			<view class="card_nav">
				<view class="card_one">
					<view class="card_four">
						超级客户年票
					</view>
					<view class="card_five">
						hot
					</view>
				</view>
				<view class="card_two">
					内含3000元优惠券
				</view>
				<view class="card_three">
					<view class="card_six">
						￥
					</view>
					<view class="card_seven">
						1800
					</view>
					<view class="card_eight">
						销量 456879
					</view>
				</view>
			</view>
			<view class="card_logo">
				
			</view>
		</view>
		
		
		<view class="style">
			<view class="style_size style_backg1 gap">
				<view class="style_tit">
					甜美型
				</view>
				<view class="style_line">
					
				</view>
			</view>
			<view class="style_size style_backg2 gap">
				<view class="style_tit">
					可爱型
				</view>
				<view class="style_line">
					
				</view>
			</view>
			<view class="style_size style_backg3 gap">
				<view class="style_tit">
					帅气型
				</view>
				<view class="style_line">
					
				</view>
			</view>
			<view class="style_size style_backg4">
				<view class="style_tit">
					性感型
				</view>
				<view class="style_line">
					
				</view>
			</view>
		</view>
		
		
		<scroll-view class="hair" scroll-x="true" style=" width: 100%;white-space: nowrap; display: inline-block">
			<view class="hair_left">
				<view class="hair_image">
					<view class="hair_button">
						韩式发型
					</view>
				</view>
				<view class="hair_tit">
					<view class="">
						高级感韩式发型
					</view>
					<view class="hair_style">
						卷度与发色造仙气
					</view>
				</view>
			</view>
			<view class="hair-r">
				<view class="hair_image">
					<view class="hair_button">
						精灵短发
					</view>
				</view>
				<view class="hair_tit">
					<view class="">
						郭采洁同款短发
					</view>
					<view class="hair_style">
						矮个子女生发型
					</view>
				</view>
			</view>
		</scroll-view>
		
		
		
		<view class="section section_gap">
		  <view class="section__title">horizontal scroll</view>
		  <scroll-view class="scroll-view_H" scroll-x="true" style="width: 100%; white-space: nowrap; display: flex">
		    <view id="green" class="scroll-view-item_H bc_green"></view>
		    <view id="red"  class="scroll-view-item_H bc_red"></view>
		    <view id="yellow" class="scroll-view-item_H bc_yellow"></view>
		    <view id="blue" class="scroll-view-item_H bc_blue"></view>
		  </scroll-view>
		</view>
		
		
		<view class="hair_icon">
			<view class="icon-size icon_gad ">
				<view class="hair-icons">
					1
				</view>
				<view class="hair_name">
					烫发
				</view>
				
			</view>
			<view class="icon-size icon_gad ">
				<view class="hair-icons">
					
				</view>
				<view class="hair_name">
					烫发
				</view>
			</view>
			<view class="icon-size icon_gad ">
				<!-- <view class="hair-icons">
					
				</view> -->
				<view class="hair_name">
					烫发
				</view>
			</view>
			<view class="icon-size">
				<!-- <view class="hair-icons">
					
				</view> -->
				<view class="hair_name">
					烫发
				</view>
			</view>
		</view>
		
		<view class="chinese">
			<view class="chinese_card card_gad">
				<view class="chinese_box">
					<view class="chinese_title">
						课程精讲
					</view>
					<view class="chinese_active">
						动词大比拼
					</view>
				</view>
				<view class="box_transform">
					
				</view>
			</view>
			<view class="chinese_card">
				
			</view>
		</view>
		<view class="fashion-box">
			<view class="fashiontitle">fashion horizontal scroll</view>
			<scroll-view class="fashion_scroll-view_H" scroll-x="true" style="width: 100%; white-space: nowrap; display: inline-block">
			  <view id="green" class="fashion_scroll-view bc_green fashion_gad">
				<view class="fashion_brank">
				  	<view class="fashion_name">
				  		MAMAN
				  	</view>
				  	<view class="fashion_cont">
				  		dazhonghua
				  	</view>
				</view>
				  
			  </view>
			  <view id="red"  class="fashion_scroll-view bc_red fashion_gad">
				  <view class="fashion_brank">
				    	<view class="fashion_name">
				    		MAMAN
				    	</view>
				    	<view class="fashion_cont">
				    		dazhonghua
				    	</view>
				  </view>
			  </view>
			  <view id="yellow" class="fashion_scroll-view bc_yellow fashion_gad">
				  <view class="fashion_brank">
				    	<view class="fashion_name">
				    		MAMAN
				    	</view>
				    	<view class="fashion_cont">
				    		dazhonghua
				    	</view>
				  </view>
			  </view>
			  <view id="blue" class="fashion_scroll-view bc_blue">
				  <view class="fashion_brank">
				    	<view class="fashion_name">
				    		MAMAN
				    	</view>
				    	<view class="fashion_cont">
				    		dazhonghua
				    	</view>
				  </view>
			  </view>
			</scroll-view>
			
		</view>
	</view>
</template>

<script>
	// var order = ['red', 'yellow', 'blue', 'green', 'red']
	// Page({
	//   data: {
	//     toView: 'red',
	//     scrollTop: 100
	//   },
	//   upper: function(e) {
	//     console.log(e)
	//   },
	//   lower: function(e) {
	//     console.log(e)
	//   },
	//   scroll: function(e) {
	//     console.log(e)
	//   },
	//   tap: function(e) {
	//     for (var i = 0; i < order.length; ++i) {
	//       if (order[i] === this.data.toView) {
	//         this.setData({
	//           toView: order[i + 1]
	//         })
	//         break
	//       }
	//     }
	//   },
	//   tapMove: function(e) {
	//     this.setData({
	//       scrollTop: this.data.scrollTop + 10
	//     })
	//   }
	// })

// 	export default {
// 		data() {
// 			hotList: [
// 			        {
// 			            pic: '/images/example2.png',
// 			            title: '玻璃棧道',
// 			            desc: '22W人去過'
// 			        }, {
// 			            pic: '/images/example2.png',
// 			            title: '玻璃棧道',
// 			            desc: '22W人去過'
// 			        }, {
// 			            pic: '/images/example2.png',
// 			            title: '玻璃棧道',
// 			            desc: '22W人去過'
// 			        }, {
// 			            pic: '/images/example2.png',
// 			            title: '玻璃棧道',
// 			            desc: '22W人去過'
// 			        }, {
// 			            pic: '/images/example2.png',
// 			            title: '玻璃棧道',
// 			            desc: '22W人去過'
// 			        }]
// 
// 			return {
// 				title: 'Hello'
// 			}
// 		},
// 		onLoad() {
// 
// 		},
// 		methods: {
// 
// 		}
// 	}
</script>

<style>
@import url("../test_pages/test.css");
</style>