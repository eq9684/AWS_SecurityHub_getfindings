# AWS_SecurityHub_getfindings
aws securityhub get-findings 如果返回数据量太大的话，会返回TooManyRequestException错误，
如果用Paging分页，需要获取每一页的NextToken作为下一页的starting-token参数
