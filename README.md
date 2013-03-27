Date
====
//计算加一个月后的日期
日期
public static void main(String[] args) {
		
        Calendar ca = Calendar.getInstance();
        ca.setTime(new Date());
        ca.add(Calendar.MONTH, +1);
        Date result=ca.getTime();
        SimpleDateFormat sdf = new SimpleDateFormat("yyyy-MM");
        System.out.println(sdf.format(result));

		System.out.println(DataFormat.getCurrDateStr());
		System.out.println(new SimpleDateFormat("yyyy-MM").format(new Date()));
	}
