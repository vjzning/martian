var _ = require('underscore');
var async = require('async');
var t = [
	{
		"id": 4,
		"task_id": 1,
		"user_id": 7,
		"type": "2",
		"value": "1",
		"create_time": 1419067214,
		"update_time": 1419332946
	},
	{
		"id": 5,
		"task_id": 1,
		"user_id": 7,
		"type": "5",
		"value": "1",
		"create_time": 1419072405,
		"update_time": 1419332946
	},
	{
		"id": 1,
		"task_id": 1,
		"user_id": 9,
		"type": "2",
		"value": "1",
		"create_time": 1419066549,
		"update_time": 1419332946
	},
	{
		"id": 6,
		"task_id": 1,
		"user_id": 9,
		"type": "5",
		"value": "1",
		"create_time": 1419074186,
		"update_time": 1419332946
	},
	{
		"id": 2,
		"task_id": 1,
		"user_id": 10,
		"type": "1",
		"value": "1",
		"create_time": 1419066878,
		"update_time": 1419332946
	},
	{
		"id": 3,
		"task_id": 1,
		"user_id": 10,
		"type": "4",
		"value": "1",
		"create_time": 1419066878,
		"update_time": 1419332946
	},
	{
		"id": 12,
		"task_id": 1,
		"user_id": 10,
		"type": "5",
		"value": "1",
		"create_time": 1419317298,
		"update_time": 1419332946
	}
];
var ret = _.filter(t, function(item){
	return item.type == 2;
});

console.log(_.pluck(ret, 'user_id'));
console.log(_.pluck([], 'a'));
var str = '';
str.match(/((http|ftp|https|file):[^'"\s]+)/ig);
