# JavaLearningss
This repository contains javaprograms
package javaProgram;

public class Bankaccount {
	Long accountNumber=3334445558765l;
	String name="Priya";
	int balance=50000;
	private int debitamount() {
		System.out.println("The debit amount is: xxxxx");
		return balance;
	}
	public void withdrawal() {
		System.out.println("You Successfully with drawn the amount");
	}
	private Long myacno() {
		System.out.println("My account number is **********651");
		return accountNumber;
	}
	private String myname() {
		System.out.println("Dear piya");
		return name;
	}
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Bankaccount bankaccount=new Bankaccount();
		bankaccount.withdrawal();
		bankaccount.debitamount();
		int ac=bankaccount.debitamount();
		System.out.println("My current balance is:"+ac);
		Long ano=bankaccount.myacno();
		System.out.println("My account number is:"+ano);
		String aname=bankaccount.myname();
		System.out.println("the account holder name is:"+aname);

	}

}
