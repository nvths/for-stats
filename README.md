//	System.out.println	("the city you starty out in is "+ cityes);
	System.out.println	("please pick your class");
	System.out.println	("0 - barbarian /" + " 1 - bard /" + " 2 - cleric /" + " 3 - druid /"+" 4 - fighter /"+" 5 - monk /" + " 6 - paladin /" + " 7 - ranger /" + " 8 - sorcerer /" + " 9 - wizard");	
	int classesin			= input.nextInt();
	String classese 		= classes.playersclass(classesin);
	System.out.println	("0 - human /"+ " 1 - elf /"+" 2 - dwarf /"+ " 3 - halfling /"+ " 4 - half elf /"+ " 5 - half orc /" +" 6 - gnome");
	int raceses				= input.nextInt( );
	String races 			= classes.playersrace(raceses);
	System.out.println("you are a "+ races + " studying the art of "+ classese);
	System.out.println("please pick you alignment");
	System.out.println("0 - good /"+" 1 - neutral /"+" 2 - evil");
	int alignmentstr = input.nextInt();
	String playersstra = alignment.playersstrangth(alignmentstr);
	System.out.println("0 - lawful /"+" 1 - neutral /"+" 2 - chaotic");
	int alignmentfa = input.nextInt();
	String playersfa = alignment.playersfaith(alignmentfa);
	
	return createdid;
