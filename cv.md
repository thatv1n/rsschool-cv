## [rsschool-cv](rsccool-cv)


# Shakhov Ivan

# Contact 

* **Address:** Aymanov st. Pavlodar, Kazakhstan
* **E-mail:** [shakhov.ivan.p@gmail.com](shakhov.ivan.p@gmail.com)
* **GitHub:** [thatv1n](https://github.com/thatv1n)
* **Codewars:** [thatv1n](https://www.codewars.com/users/thatv1n)


# About me

I like the IT sphere, I follow the emergence of new technologies, I tried different directions, but most of
all I liked Web development. I made my choice in favor of the front-end direction, because you can
immediately see the result of your work, make interesting features, animations, as well as work in a
team, since you always learn something new, make new acquaintances with more experienced people,
thereby constantly evolving and not standing still.

# My Skills

* HTML
* CSS, SCSS 
* JavaScript
* TypeScript (little bit)
* React JS, Redux Toolkit, Redux Thunk, React Hook, React Router
* Version control: Git 
* Figma(for web development)
* Editors: VSCode.


# Example code

**A part task on the vacancy forntend-developer**

import { FC } from 'react';
import { Draggable } from 'react-beautiful-dnd';

import { IItemTableProps } from './interface';

import './style.scss';

export const ItemTable: FC<IItemTableProps> = ({ item, index }) => {
	return (
		<Draggable draggableId={`${index}`} key={index} index={index}>
			{(provided) => (
				<tr
					{...provided.draggableProps}
					{...provided.dragHandleProps}
					ref={provided.innerRef}
					className='item'
				>
					<td>{item.id}</td>
					<td>{item.key}</td>
					<td>{item.AssetsCurrent || '-'}</td>
					<td>{item.IncomeTaxExpenseBenefit || '-'}</td>
					<td>{item.NetIncomeLoss || '-'}</td>
					<td>{item.OperatingIncomeLoss || '-'}</td>
				</tr>
			)}
		</Draggable>
	);
};

# Language

* Russian - native
* English - A2

# My Projects

* **Funeral goods store:** [https://snabritual.ru/](https://snabritual.ru/)
* **A small shop equipments:** [https://prosvyaz.kz/](https://prosvyaz.kz/)
* **And different my works:** [https://thatv1n.github.io/Task-FNTASTIC](https://thatv1n.github.io/Task-FNTASTIC/) , [https://thatv1n.github.io/calculator/](https://thatv1n.github.io/calculator/)
